---
layout: post
title: "Bass Guitar Scale Patterns: Melodic minor"
date: 2019-10-03 12:00:00 +1100
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
    noteMode: "letter",
    // Force Eb enharmonic
    noteLetters: ["C", "C#/Db", "D", "Eb", "E", "F", "F#/Gb", "G", "Ab/G#", "A", "A#/Bb", "B"]
  };
</script>

# Sequence

`TSTTTTS`

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
      fret: 6,
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
    notes: [
  {
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
      fret: 6,
      cssClass: "grey"
  },
  {
      fret: 8,
      cssClass: "grey"
  }],
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
  }],
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
      fret: 8,
      cssClass: "grey"
  }],
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
      fret: 8,
      cssClass: "blue"
  },
  {
      fret: 10,
      cssClass: "grey"
  },
  {
      fret: 11,
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
      fret: 7,
      cssClass: "lightgrey"
  },
  {
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
      fret: 7,
      cssClass: "lightgrey"
  },
  {
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
      fret: 10,
      cssClass: "grey"
  },
  {
      fret: 11,
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
  },
  {
    string: {
      letter: "D",
      octave: 3
    },
    notes: [{
      fret: 10,
      cssClass: "blue"
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

  api.setClickedNotes(patt5Notes);
})(jQuery);
</script>
