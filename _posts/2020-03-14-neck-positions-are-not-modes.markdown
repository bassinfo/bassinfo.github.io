---
layout: post
title: "Neck positions are not modes"
date: 2020-03-14 12:00:00 +1100
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

# The conception

More than a handful of guitarists learn a way to remember scale patterns which involves also learning a misconception of what *"modes"* are, and leading to a way of speaking about them which sounds like gibberish to many of their fellow musicians.

The idea is that up and down the neck of the guitar are various *"modes"*. As you move up the neck starting each pattern on the index finger and counting from there you have an *interval construction* which matches that of a mode.

## "F Lydian"

<div id="lydian"></div>

<script type="application/javascript">
(function($) {

  $("#lydian").fretboard(opts);
  var api = $("#lydian").data('api');

  var lydianNotes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [
    {
      fret: 1,
      cssClass: "blue"
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
    notes: [
    {
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
      letter: "D",
      octave: 3
    },
    notes: [
    {
      fret: 2,
      cssClass: "grey"
    },
    {
      fret: 3,
      cssClass: "blue"
    },
    {
      fret: 5,
      cssClass: "lightgrey"
    }],
  },
  {
    string: {
      letter: "G",
      octave: 3
    },
    notes: [
    {
      fret: 2,
      cssClass: "lightgrey"
    },
    {
      fret: 4,
      cssClass: "lightgrey"
    },
    {
      fret: 5,
      cssClass: "lightgrey"
    }],
  }];

  api.setClickedNotes(lydianNotes);
})(jQuery);
</script>

Now this absolutely is *"F Lydian"*. It has a `#4` and is a great pattern for playing *Lydian* sounds.


## "G Mixolydian"

<div id="mixo"></div>

<script type="application/javascript">
(function($) {

  $("#mixo").fretboard(opts);
  var api = $("#mixo").data('api');

  var mixoNotes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [
    {
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
      letter: "A",
      octave: 2
    },
    notes: [
    {
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
      letter: "D",
      octave: 3
    },
    notes: [
    {
      fret: 3,
      cssClass: "grey"
    },
    {
      fret: 5,
      cssClass: "blue"
    },
    {
      fret: 7,
      cssClass: "lightgrey"
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
      cssClass: "lightgrey"
    },
    {
      fret: 5,
      cssClass: "lightgrey"
    },
    {
      fret: 7,
      cssClass: "lightgrey"
    }],
  }];

  api.setClickedNotes(mixoNotes);
})(jQuery);
</script>

Once again, absolutely *"G Mixolydian"*. Has a `b7` and is a common way of accessing Mixolydian tonality.

Continue this naming convention up the fretboard, placing the **index finger** on each successive note and calling that the new tonic then generating a mode from there.

# The misconception

Given that each mode is simply a rotation of the Major scale, problems arise when this is then used as the name for this way of playing that Major scale. If we see this fragment of the Major scale on the guitar fretboard as being *"Lydian"* then apply that as a context things quickly get confusing.

*"I'm playing F Lydian over B."*

What does someone mean by this?

Well if we understand the context of remembering the above neck position as a *"mode"* then it starts to make sense.

<div id="blydian"></div>

<script type="application/javascript">
(function($) {

  $("#blydian").fretboard(opts);
  var api = $("#blydian").data('api');

  var blydianNotes = [{
    string: {
      letter: "E",
      octave: 2
    },
    notes: [
    {
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
    notes: [
    {
      fret: 2,
      cssClass: "blue"
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
      letter: "D",
      octave: 3
    },
    notes: [
    {
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
    notes: [
    {
      fret: 2,
      cssClass: "grey"
    },
    {
      fret: 4,
      cssClass: "blue"
    },
    {
      fret: 5,
      cssClass: "grey"
    }],
  }];

  api.setClickedNotes(blydianNotes);
})(jQuery);
</script>

This absolutely is something which can be described as *"I'm playing F Lydian over B."*. However it's not really the tonality being played but a memory device for remembering the pattern.

Lets break that down again.

Q: Now we understand what is meant by *"F Lydian"*, but what of this *"B"*?  
A: Well that's our tonic. The root. 

Q: So what was the F again?  
A: The F was Lydian.

Q: We're in F?  
A: Nope, we're in B.

Q: So F Lydian?  
A: **Nope, B Locrian**. *"I'm playing B Locrian. Using a neck position which has the index finger on F."*. Contains an F but nothing to do with *"F"* and **nothing to do with *"Lydian"***.

# The problem

When learning neck positions we should strive to learn them end-to-end, starting whereever they start and running the width of the fretboard until the position ends. Within this position all roots/tonics are possible, all modes are contained within each position and all that's needed to bring them out is to add emphasis to the appropriate tones.

We should strive for **finger independance** and tying a mode or a particular sound to a pattern which *must* start on our **index finger** is very restrictive and goes against this goal. All modes extend from one end of the instrument to the other and aren't some specific set of fingerings.

Neck positions should not be practised in ways which then associate that neck position with a certain tonality, but instead should be available within *any* harmonic context starting on *any* finger.

# Appenditure

Discovered this video which correctly describes modes while emphasising that neck postions are not modes but instead they cover the entire fretboard. [Guitar Lesson Frank Gambale Modes, No More Mysteries](https://www.youtube.com/watch?v=5sBqMxq_214)
