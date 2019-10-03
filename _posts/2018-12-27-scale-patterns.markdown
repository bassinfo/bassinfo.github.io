---
layout: post
title: "Bass Guitar Scale Patterns: Major"
date: 2018-12-27 12:00:00 +1100
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

# Origin

Many bass players seem to focus on _"Major scale in 2 octaves"_ and then as they deal with figuring this out from various starting points develop a foundation of scale patterns across the neck.

I was taught these patterns by a GIT educated guitarist, although I see the same in Jaco Pastorius's _"Modern Electric Bass"_. Specifically _Pattern 5_ as _"Exercise 2"_ and he plays _Pattern 4_ for demonstrating diatonic 6ths in _"Exercise 7"_.

I skip seeing _Pattern 1_ and _Pattern 2_ as separate and instead construct them on-the-fly from pieces of the others. They hold more meaning for guitarists who have to deal with the 1 fret displacement of a high B string. It's possible to connect Pattern 5 to 3 and 4 both horizontally and vertically. Practically imaging them as running across more strings then are on the bass.

# Exercises

- Play everything ascending and descending.
- Play up one pattern and down the next.
- Play in diatonic 3rds, 4ths, 5ths, and 6ths.
- Also 7ths and 9ths though this may require combining patterns.

# Sequence

`TTSTTTS`

# Pattern 1

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

  api.setClickedNotes(patt1Notes);
})(jQuery);
</script>

# Pattern 2

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

# Pattern 3

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

# Pattern 4

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

# Pattern 5

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

# Sliding pattern (_Chuck Sher_)

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
