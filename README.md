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

Here shows example of generating images from 
"I Wandered Lonely as a Cloud" by William Wordsworth.

""""""""""""""""""""
I wandered lonely as a Cloud
That floats on high o'er Vales and Hills,
When all at once I saw a crowd
A host of dancing Daffodils;
Along the Lake, beneath the trees,
Ten thousand dancing in the breeze.

The waves beside them danced, but they
Outdid the sparkling waves in glee: --
A poet could not but be gay
In such a laughing company:
I gazed—and gazed—but little thought
What wealth the show to me had brought:

For oft when on my couch I lie
In vacant or in pensive mood,
They flash upon that inward eye
Which is the bliss of solitude,
And then my heart with pleasure fills,
And dances with the Daffodils.
"""""""""""""""

Result of the prompt "Create a photorealistic image that captures {}'s signature style and tone, inspired by the following line of the poem:\n\n{}"

<img width="1024" height="1024" alt="Prompt1_image2" src="https://github.com/user-attachments/assets/0ca7cac7-4cb8-4f02-8ad7-82d648b6a569" />
<img width="1024" height="1024" alt="Prompt1_image1" src="https://github.com/user-attachments/assets/b43f5775-b959-45ce-b6c0-83842ec02d79" />


Result of the prompt the prompt "Create a image that based on art style of {}'s the lived period and captured his literature signature style and tone, inspired by the following line of the poem:\n\n{}"
<img width="1024" height="1024" alt="Prompt2_image2" src="https://github.com/user-attachments/assets/7f0a9144-0b87-490c-a54c-26209a205be6" />
<img width="1024" height="1024" alt="Prompt2_image1" src="https://github.com/user-attachments/assets/29e29066-0d2a-48c7-945d-2d37fdd97767" />



