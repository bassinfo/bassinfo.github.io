---
layout: post
title: "Bass Guitar Scale Patterns: Major (Updated)"
date: 2020-06-26 12:00:00 +1100
categories: scales
---

<link rel="stylesheet" href="/assets/css/fretboard.css">

<script
  src="https://code.jquery.com/jquery-1.11.2.min.js"
  integrity="sha256-Ls0pXSlb7AYs7evhd+VLnWsZ/AqEHcXBeMZUycz/CcA="
  crossorigin="anonymous"></script>

<script type="application/javascript" src="/assets/js/fretboard.js"></script>

<script type="application/javascript">
  var bass = [{
    letter: "G",
    octave: 3
  }, {
    letter: "D",
    octave: 3
  }, {
    letter: "A",
    octave: 2
  }, {
    letter: "E",
    octave: 2
  }];

  var opts = {
    tuning: bass,
    numFrets: 18,
    isChordMode: false,
    noteClickingDisabled: true,
    noteMode: "letter"
  };
</script>

# Update

My [previous diagrams]({% post_url 2018-12-27-scale-patterns %}) were how I learnt neck positions but probably not exactly how I actually use them. Seems the main difference is addition of *Position 6* which is like an up-side-down *Position 2*. Along with the insertion of *"F Lydian"* as *Position 1* while shifting one down to *Position 0*.

# "Modes"

I've includes the names of what these neck positions would be **if the index finger were the root**. Please note that *[Neck Positions are NOT Modes]({% post_url 2020-03-14-neck-positions-are-not-modes %})*. Each of these positions can be *any* mode, it all depends on where you put the emphasis.

# Exercises

- Play everything ascending and descending.
- Play up one pattern and down the next.
- Play in diatonic 3rds, 4ths, 5ths, and 6ths.
- Also 7ths and 9ths though this may require combining patterns.
- Play in 3, 4, and 5 note runs.

# Sequence

`TTSTTTS`

# Position 0 ("E Phrygian")

<div id="patt0"></div>

<script type="application/javascript">
(function($) {

  $("#patt0").fretboard(opts);
  var api = $("#patt0").data('api');

  var patt0Notes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [{
      fret: 0,
      cssClass: "grey"
    },
    {
      fret: 1,
      cssClass: "grey"
    },
    {
      fret: 3,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "A",
      octave: 2
    },
    notes: [{
      fret: 0,
      cssClass: "grey"
    },
    {
      fret: 2,
      cssClass: "grey"
    },
    {
      fret: 3,
      cssClass: "blue"
    }],
  },
  {
    string: {
      letter: "D",
      octave: 3
    },
    notes: [{
      fret: 0,
      cssClass: "grey"
    },
    {
      fret: 2,
      cssClass: "grey"
    },
    {
      fret: 3,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "G",
      octave: 3
    },
    notes: [{
      fret: 0,
      cssClass: "grey"
    },
    {
      fret: 2,
      cssClass: "grey"
    },
    {
      fret: 4,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(patt0Notes);
})(jQuery);
</script>


# Position 1 ("F Lydian")

<div id="patt1"></div>

<script type="application/javascript">
(function($) {

  $("#patt1").fretboard(opts);
  var api = $("#patt1").data('api');

  var patt1Notes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [{
      fret: 1,
      cssClass: "grey"
    },
    {
      fret: 3,
      cssClass: "grey"
    },
    {
      fret: 5,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "A",
      octave: 2
    },
    notes: [{
      fret: 2,
      cssClass: "grey"
    },
    {
      fret: 3,
      cssClass: "blue"
    },
    {
      fret: 5,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "D",
      octave: 3
    },
    notes: [{
      fret: 2,
      cssClass: "grey"
    },
    {
      fret: 3,
      cssClass: "grey"
    },
    {
      fret: 5,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "G",
      octave: 3
    },
    notes: [{
      fret: 2,
      cssClass: "grey"
    },
    {
      fret: 4,
      cssClass: "grey"
    },
    {
      fret: 5,
      cssClass: "blue"
    }],
  }];

  api.setClickedNotes(patt1Notes);
})(jQuery);
</script>

# Position 2 ("G Mixolydian")

<div id="patt2"></div>

<script type="application/javascript">
(function($) {

  $("#patt2").fretboard(opts);
  var api = $("#patt2").data('api');

  var patt2Notes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [{
      fret: 3,
      cssClass: "grey"
    },
    {
      fret: 5,
      cssClass: "grey"
    },
    {
      fret: 7,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "A",
      octave: 2
    },
    notes: [{
      fret: 3,
      cssClass: "blue"
    },
    {
      fret: 5,
      cssClass: "grey"
    },
    {
      fret: 7,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "D",
      octave: 3
    },
    notes: [{
      fret: 3,
      cssClass: "grey"
    },
    {
      fret: 5,
      cssClass: "grey"
    },
    {
      fret: 7,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "G",
      octave: 3
    },
    notes: [{
      fret: 4,
      cssClass: "grey"
    },
    {
      fret: 5,
      cssClass: "blue"
    },
    {
      fret: 7,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(patt2Notes);
})(jQuery);
</script>

# Position 3 ("A Aeolian")

<div id="patt3"></div>

<script type="application/javascript">
(function($) {

  $("#patt3").fretboard(opts);
  var api = $("#patt3").data('api');

  var patt3Notes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [{
      fret: 5,
      cssClass: "grey"
    },
    {
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 8,
      cssClass: "blue"
    }],
  },
  {
    string: {
      letter: "A",
      octave: 2
    },
    notes: [{
      fret: 5,
      cssClass: "grey"
    },
    {
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 8,
      cssClass: "grey"
    }]
  },
  {
    string: {
      letter: "D",
      octave: 3
    },
    notes: [{
      fret: 5,
      cssClass: "grey"
    },
    {
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 9,
      cssClass: "grey"
    }]
  },
  {
    string: {
      letter: "G",
      octave: 3
    },
    notes: [{
      fret: 5,
      cssClass: "blue"
    },
    {
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 9,
      cssClass: "grey"
    }]
  }];

  api.setClickedNotes(patt3Notes);
})(jQuery);
</script>


# Position 3a (Variation)

<div id="patt3a"></div>

<script type="application/javascript">
(function($) {

  $("#patt3a").fretboard(opts);
  var api = $("#patt3a").data('api');

  var patt3aNotes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [{
      fret: 5,
      cssClass: "grey"
    },
    {
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 8,
      cssClass: "blue"
    }],
  },
  {
    string: {
      letter: "A",
      octave: 2
    },
    notes: [{
      fret: 5,
      cssClass: "grey"
    },
    {
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 8,
      cssClass: "grey"
    }]
  },
  {
    string: {
      letter: "D",
      octave: 3
    },
    notes: [{
      fret: 5,
      cssClass: "grey"
    },
    {
      fret: 7,
      cssClass: "grey"
    }]
  },
  {
    string: {
      letter: "G",
      octave: 3
    },
    notes: [{
      fret: 4,
      cssClass: "grey"
    },
    {
      fret: 5,
      cssClass: "blue"
    },
    {
      fret: 7,
      cssClass: "grey"
    }]
  }];

  api.setClickedNotes(patt3aNotes);
})(jQuery);
</script>

# Position 4 ("B Locrian")

<div id="patt4"></div>

<script type="application/javascript">
(function($) {

  $("#patt4").fretboard(opts);
  var api = $("#patt4").data('api');

  var patt4Notes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [{
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 8,
      cssClass: "blue"
    },
    {
      fret: 10,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "A",
      octave: 2
    },
    notes: [{
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 8,
      cssClass: "grey"
    },
    {
      fret: 10,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "D",
      octave: 3
    },
    notes: [{
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 9,
      cssClass: "grey"
    },
    {
      fret: 10,
      cssClass: "blue"
    }],
  },
  {
    string: {
      letter: "G",
      octave: 3
    },
    notes: [{
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 9,
      cssClass: "grey"
    },
    {
      fret: 10,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(patt4Notes);
})(jQuery);
</script>

# Position 5 ("C Ionian")

<div id="patt5"></div>

<script type="application/javascript">
(function($) {

  $("#patt5").fretboard(opts);
  var api = $("#patt5").data('api');

  var patt5Notes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [{
      fret: 8,
      cssClass: "blue"
    },
    {
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "A",
      octave: 2
    },
    notes: [{
      fret: 8,
      cssClass: "grey"
    },
    {
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "D",
      octave: 3
    },
    notes: [{
      fret: 9,
      cssClass: "grey"
    },
    {
      fret: 10,
      cssClass: "blue"
    },
    {
      fret: 12,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "G",
      octave: 3
    },
    notes: [{
      fret: 9,
      cssClass: "grey"
    },
    {
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(patt5Notes);
})(jQuery);
</script>


# Position 6 ("D Dorian")

<div id="patt6"></div>

<script type="application/javascript">
(function($) {

  $("#patt6").fretboard(opts);
  var api = $("#patt6").data('api');

  var patt6Notes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [
    {
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "grey"
    },
    {
      fret: 13,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "A",
      octave: 2
    },
    notes: [
    {
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "grey"
    },
    {
      fret: 14,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "D",
      octave: 3
    },
    notes: [
    {
      fret: 10,
      cssClass: "blue"
    },
    {
      fret: 12,
      cssClass: "grey"
    },
    {
      fret: 14,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "G",
      octave: 3
    },
    notes: [{
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "grey"
    },
    {
      fret: 14,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(patt6Notes);
})(jQuery);
</script>

# Shifting pattern ("A minor")

<div id="pattSlideMinor"></div>

<script type="application/javascript">
(function($) {

  $("#pattSlideMinor").fretboard(opts);
  var api = $("#pattSlideMinor").data('api');

  var pattSlideMinorNotes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [{
      fret: 5,
      cssClass: "grey"
    },
    {
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 8,
      cssClass: "blue"
    }],
  },
  {
    string: {
      letter: "A",
      octave: 2
    },
    notes: [{
      fret: 5,
      cssClass: "grey"
    },
    {
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 8,
      cssClass: "grey"
    }]
  },
  {
    string: {
      letter: "D",
      octave: 3
    },
    notes: [{
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 9,
      cssClass: "grey"
    },
    {
      fret: 10,
      cssClass: "blue"
    }]
  },
  {
    string: {
      letter: "G",
      octave: 3
    },
    notes: [{
      fret: 7,
      cssClass: "grey"
    },
    {
      fret: 9,
      cssClass: "grey"
    },
    {
      fret: 10,
      cssClass: "grey"
    }]
  }];

  api.setClickedNotes(pattSlideMinorNotes);
})(jQuery);
</script>

# Sliding pattern (_Chuck Sher: Improvisor's Bass Method_ )

Remember, slide up with first finger and down with pinkie.

<div id="pattSlide"></div>

<script type="application/javascript">
(function($) {

  $("#pattSlide").fretboard(opts);
  var api = $("#pattSlide").data('api');

  var pattSlideNotes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [{
      fret: 8,
      cssClass: "blue"
    },
    {
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "grey"
    }
    ,
    {
      fret: 13,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "A",
      octave: 2
    },
    notes: [{
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "grey"
    },
    {
      fret: 14,
      cssClass: "grey"
    },
    {
      fret: 15,
      cssClass: "blue"
    }],
  },
  {
    string: {
      letter: "D",
      octave: 3
    },
    notes: [{
      fret: 12,
      cssClass: "grey"
    },
    {
      fret: 14,
      cssClass: "grey"
    },
    {
      fret: 15,
      cssClass: "grey"
    },
    {
      fret: 17,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "G",
      octave: 3
    },
    notes: [{
      fret: 14,
      cssClass: "grey"
    },
    {
      fret: 16,
      cssClass: "grey"
    },
    {
      fret: 17,
      cssClass: "blue"
    }],
  }];

  api.setClickedNotes(pattSlideNotes);
})(jQuery);
</script>
