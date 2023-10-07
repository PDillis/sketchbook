# Sketchbook Drawings
Sol Lewitt, the renowned conceptual artist, gave us the famed [*Wall Drawing*](https://massmoca.org/sol-lewitt/) series. In these, simple guidelines were given to his assistants to bring his ideas to the real world, giving us a taste of the current conversation regarding the use of AI tools nowadays, [much to many artists' chagrin](https://berlinartweek.de/en/article/a-shortcut-to-acceptance/).

While anyone with the desire and space to do so can reproduce these *Wall Drawings*, these were usually meant to be brought to life in large spaces, to be appreciated both at a distance and up close. In a way, this limits who can serve as a new "assistant" to Lewitt, even after years of his passing. 

The appearance of large *foundational* models such as Large Language Models (LLMs) have brought forth a new era in our interaction with data. Concretely, the *Wall Drawings* themselves can be seen as instances we wish to either extend or better understand, in particular to how an entity interprets and executes them. Which entity should be the interpreter: the LLM or the human in this process of creation?

Amy Goodchild chose the former: she tasked`ChatGPT` with [generating some the *Wall Drawings*](https://www.amygoodchild.com/blog/chatgpt-sol-lewitt-wall-drawings) (and later [compared it with the more capable `GPT-4`](https://www.amygoodchild.com/blog/ai-generations-chatgpt-4-sol-lewitt-wall-drawings)) using nothing but code in [`p5js`](https://p5js.org/). 

Note that, doing so, we're using complex tools to interpret simple instructions, and I feel the roles should be reversed: what if we let the LLM generate ***new*** simple instructions, effectively ***extending*** the Drawings themselves, and let humans do both the interpretation and its execution?

We start now by showcasing some new *Wall Drawings* that `GPT-4` has wrought before moving on to the *Sketchbook Drawings*. Note that this is an ongoing work and that you can find the full conversation log and extra attempts at *Drawings* [here](https://chat.openai.com/share/fdb41e97-ad72-47af-a342-b7ce85ff4b7d) (as of October 6th 2023, but will be continuously updated).

# Extending *Wall Drawings*
Note that it is a hard task to give, so this exercise helped gauge how much freedom we should give to `GPT-4` when creating the newer *Sketchbook Drawings*. There were no instructions on which number to start the *Wall Drawings* from, so this bias may come from the training data itself.

We start with a very vanilla attempt:
> *Wall Drawing 123*: "A wall divided into a grid of nine equal squares, three by three. Each square contains a unique geometric shape. The shapes are to be drawn using only straight lines. The lines within each shape must intersect at least once. The shapes must not repeat and each must touch at least one edge of its square."

A bit boring, but we could do better by specifying that the drawer should use only lines, avoid phrases such as "spaced evenly apart" and "...left to the discretion of the drawer" (or it would be too on the nose), we arrive to:

> *Wall Drawing 127*: "A wall divided into two equal halves vertically. The left half is filled with vertical lines of varying thickness and distance apart. The right half is filled with horizontal lines of varying thickness and distance apart. The lines in each half should not intersect or overlap. The thickness and distance of the lines should be determined by the rhythm of a chosen piece of music."

I would be remiss not to state that the last line of *Wall Drawing 127* blew me away and showed me what types of instructions I could expect or wish to generate along the model. I tried now to remove a constraint: what if we don't ask the drawer to divide the wall into bands or areas?

> *Wall Drawing 129*: "On the wall, draw a series of lines that begin at the floor and extend upward. The lines should vary in length, some reaching halfway up the wall, others extending to the ceiling. The thickness of each line should correspond to its length, with longer lines being thicker. The placement and orientation of the lines should evoke the feeling of a forest of trees."

> *Wall Drawing 130*: "Draw lines of varying lengths and thicknesses across the wall, starting from the bottom and reaching upwards. The lines should undulate and weave, creating an impression of a mountain range when viewed from afar. The lines should not intersect, but they may come close, like peaks and valleys in a landscape. The thickness of each line should subtly correspond to its perceived 'height', with 'taller' lines being thicker."

We've arrived to a state we wish `GPT-4` to generate from: infer a final result, but not explicitly state it to the drawer. Let's move on now to the *Sketchbook Drawings*.

# *Sketchbook Drawings*
The task is simple: instead of a wall, we now have only a small piece of paper or a sketchbook, where we will translate the instructions to the drawings ourselves. The unfiltered instructions will be pasted next, but these will be further refined alongside `GPT-4` in order to have a clear direction. Note that, as the number of *Drawing* increases, I am slowly letting `GPT-4` more freedom in a desired ***creative*** direction and no other.

* *Sketchbook Drawing 1*: "Using a pencil, draw a series of circles of varying sizes across the page. Each circle should intersect with at least one other, but no more than three. The intersections should create a sense of depth, as if some circles are behind or in front of others. Shade the circles accordingly to enhance this perception of depth."
* *Sketchbook Drawing 2*: "With a ballpoint pen, begin at the center of the page and draw a continuous line that spirals outward. The line should curve and loop, but never intersect with itself. As the line moves outward, it should become less dense, creating a sense of dispersion. The final loops should barely touch the edges of the page, like whispers fading into silence."
* *Sketchbook Drawing 3*: "Using a pencil, start at the top left corner of the page and draw a series of lines that extend diagonally to the right, each line slightly longer than the last. When a line reaches the edge of the page, begin the next line from the point where the previous line started. Continue this pattern until you reach the bottom right corner of the page. The result should be a series of triangular shapes, creating a sense of perspective and depth."
* *Sketchbook Drawing 4*: "Fold the paper vertically and then horizontally, creating four quadrants. Unfold after each fold. Next, fold the top right and bottom left corners to meet the center creases. Then, fold diagonally from the top left to the bottom right and unfold. Crumple the paper gently and then smooth it out, revealing a textured landscape of shadows and peaks."
* *Sketchbook Drawing 5*: "Drop a small amount of liquid at the top of the page. Watch its spread and patterns. Tilt the paper, guiding the liquid's flow. Drop more liquid, observing its interaction with existing paths. Alternate between drops and tilts until satisfied, then let dry, preserving the fluid dance on a static canvas."
* *Sketchbook Drawing 6*: "With a sketchbook and pen, walk in an open space. Draw lines influenced by your steps and sway. Let the rhythm shape circles into ovals and squares into trapezoids. Adjust to terrain changes. Continue, blending intention with movement, capturing your journey's essence."
* *Sketchbook Drawing #7*: "Place your sketchbook near a window where sunlight or moving shadows can reach it. Start with basic shapes or lines. As the day progresses, trace shifting shadows or sunlit areas every half hour. By day's end, your drawing captures the passage of time, each mark reflecting the day's moments."
* *Sketchbook Drawing #8*: "Near a window or garden, close your eyes. For food aromas, draw vertical lines; for flowers, wavy lines. Nature sounds like bird chirps or wind inspire feather-like strokes. Man-made sounds, like vehicle hums, prompt tight circles. Your drawing captures the sensory essence of your surroundings."

## Contributions
If you wish your sketch to be included in this gallery, please email submitsketchbook@gmail.com. Make sure to include the following:
* Make the title of the email be "Sketchbook Drawing #n", n being the *Drawing(s)* you'll be submitting (can be more than one per email)
* Include a scan of the sketch with the highest resolution available (on mobile, you can use [Microsoft Lens](https://play.google.com/store/apps/details?id=com.microsoft.office.officelens&pcampaignid=web_share) in lieu of a scanner)
* Include your name and date when the sketch was made (if different from when the email is sent)
* If you wish, include any other contact info (links to blogs, etc.)
