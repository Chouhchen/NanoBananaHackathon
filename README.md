The project design prompt to make the model to generate suitable images which can assist the study of this poem.

Here are some major technical design:

First, to generate multiple images based on a single prompt.
Since the example code provided by this competition only output a single image. I need to redesign the code to make it can do multiple output.
The solution is to create a list of section of the literature and a base_prompt variable to  be iterate to output the images.

Second, section the literature.
The literature is a long piece of text and just generate a single image can not help the student to understand the image. So the literature needs to be sectioned into smaller sections so to generate images which can assist the student to form for meaningful diction, imagery, and figurative language. This project uses sentence stops (".") as section strategy. Each section has images generated.

Third, considering author's ear
While one can just use any photogenic or any other art style to generate the image. Yet, it would be better to consider the major art style during author's life time and so to add more inspiration and depth to understand what the author is communicating.
Therefore the author variable is added into the code and prompt.

The system is aiming to use AI to assist literature study with a poem as example. To section the poem for more meaningful image output can have different methods rather than just by sentence stops. For this part, I would appreciate if any literature educators can add some advice so to improve the project.
