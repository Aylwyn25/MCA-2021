# MCA

## *Week 1*

MCA GitHub repository cloned and README.md file edited, as requested. The file can be found [here](https://github.com/Aylwyn25/MCA-2021/blob/master/README.md).

Answers to questions:

Q2) Central Theme: Erik Satie.

Q3) On the Petrucci Music Library, known by the acronym [IMSLP](https://www.imslp.org/), Satie's works are collated as Compositions, Collections and As Dedicatee. Furthermore, choosing one of their sub-options will take you to recordings, scores and MIDI files of the piece selected.

## *Week 2* 

10 bars of Erik Satie edited... **WOOHOO!** :tada: Personal Github page edited to represent said changes.

![Editing Comparison](https://user-images.githubusercontent.com/91611135/144060686-408cb284-803b-452e-91e1-3987b5d346ba.png)

Above shows the original score on the left, compared with the 10 bars of editing that have been committed on the right. Note that when played, the scores are unquestionably altered, but the changes on the eye can be very subtle.

## *Week 3*

Edited file in Verovio, moving forwards towards MEI manipulation. The Verovio score can be seen below (please note, whilst the page appears as code in editing format, when viewed on the [actual page](https://aylwyn25.github.io/MCA-2021/) it appears correctly):

<div id="app">Verovio is loading...</div>
<script type="module">
import 'https://www.verovio.org/javascript/app/verovio-app.js';
const options = {
defaultView: 'responsive', // default is 'responsive', alternative is 'document'
defaultZoom: 3, // 0-7, default is 4
enableResponsive: true, // default is true
enableDocument: true // default is true
}
var file = 'data/Gymnopodie 3.mei';
const app = new Verovio.App(document.getElementById("app"), options);
fetch(file)
.then(function(response) {
return response.text();
})
.then(function(text) {
app.loadData(text);
});
</script>

## *Week 4*

Python Notebook completed (local save not possible, saved to Jupyter Notebook itself). Added images of generated graphs, shown below, as well as jSymbolic analysis. Another week done!

![Piano Roll](/PianoRoll.png)

![Scatter Plot](/MyScatterPlot.png)

![Pitch Histogram](/PitchHistogram.png)

![Pitch Class Histogram jSymbolic Extracted](/PitchClassHistogramCSVExtracted.png)

## *Week 5*

Completed metadata enrichment within MEI file using the [ARC Schema](http://wiki.collex.org/index.php/Submitting_RDF) as well as the additional [MuSO Metadata Standards](https://muso.arts.gla.ac.uk/metadata-standards.html). Changes can be found within my [MEI file](https://github.com/Aylwyn25/MCA-2021/blob/master/data/Gymnopodie3EditableCopy.mei). The changes to its metadata include edition, date, response statement, name, editor, date, place of publishing, notes statement and project description.

## *Week 6*

Reading week, babyyyyyyyyyyyyyyyyyy! :trollface:


## *Week 7*

The most troublesome week, by far. Multiple edits and re-edits left me with the only week that I'm unhappy with my work. Whilst the metadata I wished to be in the file is completed and inside the code, the presentation from Verovio is not quite what I would like, which will be apparent when viewed below. I have unsuccesfully attempted to embed the program, and thus my score can be viewed [here](https://aylwyn25.github.io/MCA-2021/myMeta.html).

<div id="app">Verovio is loading...</div>
<script type="module">
import 'https://www.verovio.org/javascript/app/verovio-app.js';
const options = {
defaultView: 'responsive', // default is 'responsive', alternative is 'document'
defaultZoom: 3, // 0-7, default is 4
enableResponsive: true, // default is true
enableDocument: true // default is true
}
var file = 'MyMeta.html';
const app = new Verovio.App(document.getElementById("app"), options);
fetch(file)
.then(function(response) {
return response.text();
})
.then(function(text) {
app.loadData(text);
});
</script>

## *Week 8*

| Metadata Attribute | Track 1 | Track 2 | Track 3 |
| --- | --- | --- | --- |
| Title | Gymnopodie No.1 | Gymnopodie No.2 | Gymnopodie No.3 |
| Artist | Daniel Varsano | Riri Shimada | Jeroen van Veen |
| Composer | Erik Satie | Erik Satie | Erik Satie |
| Copyright Info | SME (on behalf of Sony Music Entertainment) | SME (on behalf of Sony Music Japan International) | Kontor New Media Music (on behalf of Brilliant Classics) |
| Genre | Minimalism | Minimalism | Minimalism |
| Source | YouTube | YouTube | YouTube |
| File/audio format | mp3 | mp3 | mp3 |
| Number of channels | 2 | 2 | 2 |
| Sample rate | 48kHz | 48 kHz | 48kHz |
| Bits per second | 320kbps | 320kbps | 320kbps |
| Duration | 3m36s | 2m55s | 4m54s |


##### *Gymnopodie No.1 Spectogram*
![Erik Satie - Gymnopedie No 1](https://user-images.githubusercontent.com/91611135/141308810-3f79eb63-07a7-4dd1-857e-673e927e7563.png)

##### *Gymnopodie No.2 Spectogram*
![Erik Satie - Gymnopedie No 2](https://user-images.githubusercontent.com/91611135/141309790-01c7cc30-e791-4643-b41c-1752bf9fd2ac.png)

##### *Gymnopodie No.3 Spectogram*
![Erik Satie - Gymnopedie No 3](https://user-images.githubusercontent.com/91611135/141309794-690b76c3-e51c-4db5-9bb1-539cb43d6235.png)

## *Week 9*

![Gnossienne No1 Screenshot](/GnossienneNo1Screenshot.png)

![MFCCHistogramsJupyter](https://user-images.githubusercontent.com/91611135/142428169-8dad8bbf-9a4e-4dc8-b9d9-2d1a0eb6b12a.png)

## *Week 10*

![3Chromagrams](https://user-images.githubusercontent.com/91611135/143461280-7c458194-9431-440e-ae66-cc97ae423961.png)

I felt it was important to put the images side-by-side; it illustrates both how similar all the images are, arguably making any differences hard to distinguish, yet also that there are different pockets of sound, highlighted with the different orange and red tones found in different areas of the chromagrams themselves.

![image](https://user-images.githubusercontent.com/91611135/143463025-a6dc7388-56f9-4916-ab1c-6c4fed82b6f8.png)

The similarity matrix of the new pieces can be seen above.

---

![image](https://user-images.githubusercontent.com/91611135/143465777-c1ac5a94-4d41-49ef-a1ff-3f81e9dfdd35.png)

.mscz opened in Musescore

![image](https://user-images.githubusercontent.com/91611135/143465958-cd02820f-3935-48be-9b3f-baa9a71874cd.png)

.mid opened in Musescore

When comparing the two scores, there are striking differences between both. Firstly, the scales are vastly different - the first appearing to have spread out the score to what would appear normal to a Western audience. The second being more convoluted, and arguably complex, by clustering the notes together in an atypical fashion.

Furthermore, the scores do not appear to play by the same rules in terms of clefs or notation. While visually they are strikingly different, by playing both audio streams as wll as viewing them, we can see the mistakes that have been made in the notation. Software and AI are impressive, but have not gotten us to the point of flawless quite yet.
