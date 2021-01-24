---
layout: post
title: "Cycle of Fifths Neck Position Exercise"
date: 2020-07-07 12:00:00 +1100
categories: exercises scales
---

<link rel="stylesheet" href="/assets/css/fretboard.css">

<script
  src="https://code.jquery.com/jquery-1.11.2.min.js"
  integrity="sha256-Ls0pXSlb7AYs7evhd+VLnWsZ/AqEHcXBeMZUycz/CcA="
  crossorigin="anonymous"></script>

<script type="application/javascript" src="/assets/js/fretboard.js"></script>

<script type="application/javascript">
  var bass4 = [{
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

  var bass7 = [{
    letter: "F",
    octave: 3
  }, {
    letter: "C",
    octave: 3
  }, {
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
  }, {
    letter: "B",
    octave: 2
  }];;

  var opts = {
    tuning: bass4,
    numFrets: 18,
    isChordMode: false,
    noteClickingDisabled: true,
    noteMode: "letter"
  };

  var opts7 = {
    tuning: bass7,
    numFrets: 18,
    isChordMode: false,
    noteClickingDisabled: true,
    noteMode: "letter"
  };
</script>

# C Major 7 string pattern

This repeating pattern is demonstrated by [Anthony Wellington](https://www.youtube.com/watch?v=L74DpDgMTzw&t=10m25s) on 7 string bass.

<!--
```
F----12-11-9----
C----12-11-9----
G----12-10-9----
D----12-10-9----
A----12-10-8----
E----12-10-8----
B----12-10-8----
```
-->

<div id="cmajor7string"></div>

<script type="application/javascript">
(function($) {

  $("#cmajor7string").fretboard(opts7);
  var api = $("#cmajor7string").data('api');

  var cmajor7stringNotes = [{
    string: {
      letter: "F",
      octave: 3
    },
    notes: [{
      fret: 12,
      cssClass: "grey"
    },
    {
      fret: 11,
      cssClass: "grey"
    },
    {
      fret: 9,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "C",
      octave: 3
    },
    notes: [{
      fret: 12,
      cssClass: "blue"
    },
    {
      fret: 11,
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
      fret: 12,
      cssClass: "grey"
    },
    {
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 9,
      cssClass: "grey"
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
      fret: 10,
      cssClass: "blue"
    },
    {
      fret: 9,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "A",
      octave: 2
    },
    notes: [{
      fret: 12,
      cssClass: "grey"
    },
    {
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 8,
      cssClass: "grey"
    }],
  },
  {
    string: {
      letter: "E",
      octave: 2
    },
    notes: [{
      fret: 12,
      cssClass: "grey"
    },
    {
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 8,
      cssClass: "blue"
    }],
  },
  {
    string: {
      letter: "B",
      octave: 2
    },
    notes: [{
      fret: 12,
      cssClass: "grey"
    },
    {
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 8,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(cmajor7stringNotes);
})(jQuery);
</script>


Staying within the same 4 string *"3 notes per string"* [neck position]({% post_url 2020-06-26-scale-patterns %}) and shifting the pattern down. Each time we move a fifth through the cycle this 7 string pattern migrates down 1 string.

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

# G Major Position 1

<!--
```
G-12-11-9--------------------------
D---------12-10-9------------------
A-----------------12-10-9----------
E-------------------------12-10-8--
```
-->

<div id="gmajorposition0"></div>

<script type="application/javascript">
(function($) {

  $("#gmajorposition0").fretboard(opts);
  var api = $("#gmajorposition0").data('api');

  var gmajorposition0Notes = [{
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
      cssClass: "blue"
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
  }];

  api.setClickedNotes(gmajorposition0Notes);
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

<div id="dmajorposition4"></div>

<script type="application/javascript">
(function($) {

  $("#dmajorposition4").fretboard(opts);
  var api = $("#dmajorposition4").data('api');

  var dmajorposition4Notes = [{
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

  api.setClickedNotes(dmajorposition4Notes);
})(jQuery);
</script>

# A Major Position 0

<!--
```
G-13-11-9--------------------------
D---------12-11-9------------------
A-----------------12-11-9----------
E-------------------------12-10-9--
```
-->

<div id="amajorposition0"></div>

<script type="application/javascript">
(function($) {

  $("#amajorposition0").fretboard(opts);
  var api = $("#amajorposition0").data('api');

  var amajorposition0Notes = [{
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
      fret: 11,
      cssClass: "grey"
    },
    {
      fret: 13,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(amajorposition0Notes);
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

<div id="emajorposition3"></div>

<script type="application/javascript">
(function($) {

  $("#emajorposition3").fretboard(opts);
  var api = $("#emajorposition3").data('api');

  var emajorposition3Notes = [{
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

  api.setClickedNotes(emajorposition3Notes);
})(jQuery);
</script>

# B Major Position 6

<!--
```
G-13-11-9--------------------------
D---------13-11-9------------------
A-----------------13-11-9----------
E-------------------------12-11-9--
```
-->

<div id="bmajorposition6"></div>

<script type="application/javascript">
(function($) {

  $("#bmajorposition6").fretboard(opts);
  var api = $("#bmajorposition6").data('api');

  var bmajorposition6Notes = [{
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
      fret: 13,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(bmajorposition6Notes);
})(jQuery);
</script>

# F# Major Position 2

<!--
```
G-13-11-10--------------------------
D----------13-11-9------------------
A------------------13-11-9----------
E--------------------------13-11-9--
```
-->

<div id="fsharpmajorposition2"></div>

<script type="application/javascript">
(function($) {

  $("#fsharpmajorposition2").fretboard(opts);
  var api = $("#fsharpmajorposition2").data('api');

  var fsharpmajorposition2Notes = [{
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

  api.setClickedNotes(fsharpmajorposition2Notes);
})(jQuery);
</script>

# C# Major Position 5

<!--
```
G-13-11-10---------------------------
D----------13-11-10------------------
A-------------------13-11-9----------
E---------------------------13-11-9--
```
-->

<div id="csharpposition5"></div>

<script type="application/javascript">
(function($) {

  $("#csharpposition5").fretboard(opts);
  var api = $("#csharpposition5").data('api');

  var csharpposition5Notes = [{
    string: {
      letter: "E",
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
      cssClass: "grey"
    },
    {
      fret: 13,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(csharpposition5Notes);
})(jQuery);
</script>

# Ab Major Position 1

<!--
```
G-13-12-10----------------------------
D----------13-11-10-------------------
A-------------------13-11-10----------
E----------------------------13-11-9--
```
-->

<div id="aflatmajorposition0"></div>

<script type="application/javascript">
(function($) {

  $("#aflatmajorposition0").fretboard(opts);
  var api = $("#aflatmajorposition0").data('api');

  var aflatmajorposition0Notes = [{
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
  },
  {
    string: {
      letter: "D",
      octave: 3
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
      fret: 13,
      cssClass: "blue"
    }],
  }];

  api.setClickedNotes(aflatmajorposition0Notes);
})(jQuery);
</script>

# Eb Major Position 4

<!--
```
G-13-12-10-----------------------------
D----------13-12-10--------------------
A-------------------13-11-10-----------
E----------------------------13-11-10--
```
-->

<div id="eflatmajorposition4"></div>

<script type="application/javascript">
(function($) {

  $("#eflatmajorposition4").fretboard(opts);
  var api = $("#eflatmajorposition4").data('api');

  var eflatmajorposition4Notes = [{
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
      cssClass: "blue"
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
      fret: 10,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "grey"
    },
    {
      fret: 13,
      cssClass: "blue"
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
      fret: 13,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(eflatmajorposition4Notes);
})(jQuery);
</script>

# Bb Major Position 0

<!--
```
G-14-12-10-----------------------------
D----------13-12-10--------------------
A-------------------13-12-10-----------
E----------------------------13-11-10--
```
-->

<div id="bflatmajorposition0"></div>

<script type="application/javascript">
(function($) {

  $("#bflatmajorposition0").fretboard(opts);
  var api = $("#bflatmajorposition0").data('api');

  var bflatmajorposition0Notes = [{
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
      fret: 13,
      cssClass: "blue"
    }],
  },
  {
    string: {
      letter: "D",
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

  api.setClickedNotes(bflatmajorposition0Notes);
})(jQuery);
</script>

# F Major Position 3

<!--
```
G-14-12-10-----------------------------
D----------14-12-10--------------------
A-------------------13-12-10-----------
E----------------------------13-12-10--
```
-->

<div id="fmajorposition3"></div>

<script type="application/javascript">
(function($) {

  $("#fmajorposition3").fretboard(opts);
  var api = $("#fmajorposition3").data('api');

  var fmajorposition3Notes = [{
    string: {
      letter: "E",
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
      fret: 13,
      cssClass: "blue"
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
      letter: "G",
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
      fret: 14,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(fmajorposition3Notes);
})(jQuery);
</script>

# C Major Position 6

Continuing to the next *Position 5* to demonstrate the pattern more clearly.

<!---
```
G-14-12-10-----------------------------
D----------14-12-10--------------------
A-------------------14-12-10-----------
E----------------------------13-12-10--
```
-->

<div id="cmajorposition6"></div>

<script type="application/javascript">
(function($) {

  $("#cmajorposition6").fretboard(opts);
  var api = $("#cmajorposition6").data('api');

  var cmajorposition6Notes = [{
    string: {
      letter: "E",
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

  api.setClickedNotes(cmajorposition6Notes);
})(jQuery);
</script>

# G Major Position 2

<!--
```
G-14-12-11-----------------------------
D----------14-12-10--------------------
A-------------------14-12-10-----------
E----------------------------14-12-10--
```
-->

<div id="gmajorposition2"></div>

<script type="application/javascript">
(function($) {

  $("#gmajorposition2").fretboard(opts);
  var api = $("#gmajorposition2").data('api');

  var gmajorposition2Notes = [{
    string: {
      letter: "E",
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
      letter: "A",
      octave: 2
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
      letter: "G",
      octave: 3
    },
    notes: [{
      fret: 11,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "blue"
    },
    {
      fret: 14,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(gmajorposition2Notes);
})(jQuery);
</script>

# D Major Position 5

<!--
```
G-14-12-11-----------------------------
D----------14-12-11--------------------
A-------------------14-12-10-----------
E----------------------------14-12-10--
```
-->

<div id="dmajorposition5"></div>

<script type="application/javascript">
(function($) {

  $("#dmajorposition5").fretboard(opts);
  var api = $("#dmajorposition5").data('api');

  var dmajorposition5Notes = [{
    string: {
      letter: "E",
      octave: 2
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
      fret: 14,
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
      fret: 11,
      cssClass: "grey"
    },
    {
      fret: 12,
      cssClass: "blue"
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
      fret: 11,
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

  api.setClickedNotes(dmajorposition5Notes);
})(jQuery);
</script>
