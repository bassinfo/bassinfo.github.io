---
layout: post
title: "Neck Positions Descending by Major 2nds Exercise"
date: 2020-07-08 12:00:00 +1100
categories: exercises, scales
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

# C Major Position 5

<!--
```
G-12-10-9--------------------------
D---------12-10-9------------------
A-----------------12-10-8----------
E-------------------------12-10-8--
```
-->

<div id="cmajorposition5"></div>

<script type="application/javascript">
(function($) {

  $("#cmajorposition5").fretboard(opts);
  var api = $("#cmajorposition5").data('api');

  var cmajorposition5Notes = [{
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

  api.setClickedNotes(cmajorposition5Notes);
})(jQuery);
</script>

# Bb Major Position 6

<!--
```
G-12-10-8--------------------------
D---------12-10-8------------------
A-----------------12-10-8----------
E-------------------------11-10-8--
```
-->

<div id="dflatmajorposition6"></div>

<script type="application/javascript">
(function($) {

  $("#dflatmajorposition6").fretboard(opts);
  var api = $("#dflatmajorposition6").data('api');

  var dflatmajorposition6Notes = [{
    string: {
      letter: "E",
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
      letter: "G",
      octave: 3
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
  }];

  api.setClickedNotes(dflatmajorposition6Notes);
})(jQuery);
</script>

# Ab Major Position 0

<!--
```
G-12-10-8--------------------------
D---------11-10-8------------------
A-----------------11-10-8----------
E-------------------------11-9-8--
```
-->

<div id="abmajorposition0"></div>

<script type="application/javascript">
(function($) {

  $("#abmajorposition0").fretboard(opts);
  var api = $("#abmajorposition0").data('api');

  var abmajorposition0Notes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [{
      fret: 8,
      cssClass: "grey"
    },
    {
      fret: 9,
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
      fret: 11,
      cssClass: "blue"
    }],
  },
  {
    string: {
      letter: "D",
      octave: 3
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
      fret: 11,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "G",
      octave: 3
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
  }];

  api.setClickedNotes(abmajorposition0Notes);
})(jQuery);
</script>

# F# Major Position 1

<!--
```
G-11-10-8--------------------------
D---------11-9-8------------------
A-----------------11-9-8----------
E-------------------------11-9-7--
```
-->

<div id="fsharpposition1"></div>

<script type="application/javascript">
(function($) {

  $("#fsharpposition1").fretboard(opts);
  var api = $("#fsharpposition1").data('api');

  var fsharpposition1Notes = [{
    string: {
      letter: "E",
      octave: 2
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
      fret: 9,
      cssClass: "blue"
    },
    {
      fret: 11,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "D",
      octave: 3
    },
    notes: [{
      fret: 8,
      cssClass: "grey"
    },
    {
      fret: 9,
      cssClass: "grey"
    },
    {
      fret: 11,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "G",
      octave: 3
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
      fret: 11,
      cssClass: "blue"
    }],
  }];

  api.setClickedNotes(fsharpposition1Notes);
})(jQuery);
</script>


# F# Major Position 2

<!--
```
G-11-10-8--------------------------
D---------11-9-8------------------
A-----------------11-9-8----------
E-------------------------11-9-7--
```
-->

<div id="fsharpposition2"></div>

<script type="application/javascript">
(function($) {

  $("#fsharpposition2").fretboard(opts);
  var api = $("#fsharpposition2").data('api');

  var fsharpposition2Notes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [{
      fret: 9,
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
      fret: 9,
      cssClass: "blue"
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
      letter: "D",
      octave: 3
    },
    notes: [{
      fret: 9,
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
      letter: "G",
      octave: 3
    },
    notes: [{
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 11,
      cssClass: "blue"
    },
    {
      fret: 13,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(fsharpposition2Notes);
})(jQuery);
</script>

# E Major Position 3

<!--
```
G-13-11-9--------------------------
D---------13-11-9------------------
A-----------------12-11-9----------
E-------------------------12-11-9--
```
-->

<div id="eflatposition3"></div>

<script type="application/javascript">
(function($) {

  $("#eflatposition3").fretboard(opts);
  var api = $("#eflatposition3").data('api');

  var eflatposition3Notes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [{
      fret: 9,
      cssClass: "grey"
    },
    {
      fret: 11,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "blue"
    }],
  },
  {
    string: {
      letter: "A",
      octave: 2
    },
    notes: [{
      fret: 9,
      cssClass: "grey"
    },
    {
      fret: 11,
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
      letter: "G",
      octave: 3
    },
    notes: [{
      fret: 9,
      cssClass: "blue"
    },
    {
      fret: 11,
      cssClass: "grey"
    },
    {
      fret: 13,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(eflatposition3Notes);
})(jQuery);
</script>

# D Major Position 4

<!--
```
G-12-11-9--------------------------
D---------12-11-9------------------
A-----------------12-10-9----------
E-------------------------12-10-9--
```
-->

<div id="dflatposition4"></div>

<script type="application/javascript">
(function($) {

  $("#dflatposition4").fretboard(opts);
  var api = $("#dflatposition4").data('api');

  var dflatposition4Notes = [{
    string: {
      letter: "E",
      octave: 2
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
      letter: "A",
      octave: 2
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
      fret: 11,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "blue"
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
      fret: 11,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(dflatposition4Notes);
})(jQuery);
</script>
