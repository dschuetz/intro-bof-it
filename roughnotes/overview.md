# Rough overview of project / what to do

## Background Docs

* Mission Statement
* Improve the main README with actual text
* Need better description for the goals of the project
* Perhaps some background information for why we thing it'd be useful
    * big contests very competitive
    * no sharing of information or techniquies (players wanna win!)
    * new people playing for fun or to learn can be intimidated
* And what we're *not* trying to do
    * full-day training
    * multi-day training
    * main-line conference presentations
* And can it grow beyond just contest/village like topics?
    * could eventually support technical topics
    * 1 hour overview on using Hopper Dissassembler, for example
    * or quick intro to iOS hacking


## Structure of project / "Deliverables"

* Really, not much of a "project" here, as such
* Documents / slides / exercises for a variety of classes anyone can teach
* A high-level document or template for future classes (what do we need, etc.)

So a bunch of classes, and a process to build and maintain them.


## Folder structure 

### Overall

* top level 
    * readme
    * background doc(s)
    * class template
    * classes
        * class1-level1
            * stuff for class 1 at level 1
        * class2-level2
        * ..etc..
    * rough notes (if we need to keep them around)
* can separate out development, etc., into different branches


### Individual classes

* start with a template, and it can be tweaked as necessary
* TopicName-level ("CryptoPuzzles-Intro" or "WirelessCTF-Advanced")
    * README.md - details for class (audience, expected level, goals, etc.)
    * slides.pdf - class slides in a portable, cross-platform, format, ready for projection
    * slides.ppt, slides.key - in powerpoint or keynote or whatever format (if someone chooses to build them)
    * handouts.pdf - a printer-ready copy of slides with speaker notes to be handed out
    * AnythingElse.pdf - exercises, supplemental information, history, etc.
    * slides-source/ - folder with source for slides
        * slides.md - plaintext copy of all the slides for portability
        * [images] - various images, graphics, or other stuff
        * .md - a plaintext version 
    * AnythingElse-source - etc.
* if there are multiple sets of slides + exercies + etc. (shouldn't be -- we don't want these to be long classes) then group them together in separate folders
* Offerings.md - simple list of dates/locations that it's been given
* Feedback.md - feedback from various offerings, most recent on top


