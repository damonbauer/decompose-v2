# decompose-v2
decompose talk for engineering biweekly

## Editing Slides
Located in [`index.md`](https://github.com/damonbauer/decompose-v2/blob/master/index.md).

Slides are separated by horizontal rules, using `---`.

### Slide Structure
You shouldn't have to worry about structuring content using cascading heading sizes or anything like that. [big](https://github.com/tmcw/big) will handle sizing the text.

### Images
Place any images in an `images` folder in the root folder so they can stay organized. Then it should be a [standard markdown image reference](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#images).

Images are kinda weird in the `big` framework, so [@damonbauer](https://github.com/damonbauer) can probably hack a clunky solution together if necessary.

### Videos
Since Markdown can handle regular HTML, a standard YouTube embed _should_ work just fine.

## Previewing the Presentation
In a terminal, navigate to the project folder.

* Run `yarn` to install packages (you only need to do this once after cloning the project).
* Run `big-presentation-compose -t dark` to compile the markdown into slides.
* Run `big-presentation-serve` and open the link provided.
