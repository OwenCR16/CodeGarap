# Code-Garap

## Description
All of the players in a Javanese Gamelan play using the same series of musical notes - a balungan (melody). Each performer plays something different, depending on the instrument being played.

This application takes a user-defined balungan and produces an output containing a list of basic representations of how some of the instruments from the Javanese gamelan ensemble would play said balungan. The technique for each instrument utilises unique logic in order to process the balungan into its own series of notes that it would play.
The app is mainly intended for educational use, based around the javanese gamelan but also about C# (features regarding this may be added in the future). It may also serve a use for composers who want to quickly realise a balungan's interpretation, or find potential issues.

**Disclaimer: This application serves as a demonstration. It does not provide a replacement for a real player's garap (interpretation), which contains a level of depth that lies outside the scope of said demonstration. The logic within the code is solely based on the knowledge and research of the developer. Thus, while the code is written in order to garap with consistent logic across different balungans (series of notes/inputs), it will likely make disputable choices in some generations.**

**Additionally, many common techniques used with certain instruments such as sekaran (alternate patterns anticipating the seleh played on the bonang) are not included here. The developer felt that it would be inappropriate to imitate something that is determined by organic and cultural factors with depth too significant for a utilitarian application, and something that the developer lacks sufficient personal experience with.**

## Features
The user can alter a series of variables which constrain what you can input, such as the amount of notes, or the scales which the notes sit in (pathet). They can also change options which affect the output of the application, such as selecting which parts to display. Many other features and options have been added to aid the user:

+ Transposition from one pathet to another (currently only using slendro manyura, slendro sanga, and pelog barang)
+ A toggle below the output field which allows the user to freely edit the text field (e.g. in order to allow for more in-depth educational use)
+ A setting which alters which notes the kempul plays by default, which is common in real garap (playing/interpreting the balungan)
+ A setting which alters the style and/or the rules the peking follows
+ Multiple settings which alter the patterns the bonang play

## Future Planned Features
+ Visual updates to make the UI more intuitive
+ Audio playback - having the option to listen to the output, through the use of midi
+ The availability of other colotomic structures besides a ladrang
+ The ability to save preset balungan to a user account, or to save text files directly
+ The ability to display stretched parts that line up in time (with a horizontal scroll bar)
+ Other pieces of educational material, such as a quiz on a separate page, or information on C#
+ More accurate peking logic for the setting "Pekingan doubling rules toggle" (see here for a demonstration of these rules)
+ More advanced notation and techniques, such as dots to represent octaves, and common sekaran for bonang

## How to use
Follow this link to reach the application, hosted on GitHub Pages: https://owencr16.github.io/CodeGarap/

For tutorials and basic information about the ensemble, see the Help/About pages of the application.
