# Manim-Bar-Chart-Race

A while ago, I made a YouTube video about bar chart animations using a [Matplotlib-based library](https://youtu.be/9hqGRehzEsI?si=zs9AtEbiplEue32U) and now wish to recreate the project using Manim.
In case you prefer to read, I also wrote a blog post about how to install and use Manim here:

https://andresberejnoi.com/using-manim-and-python-to-create-animations-like-3blue1brown/

I'll make a new YouTube video based on this project and there will be a link to the blog post here.

### Using Manim's BarChart Class
Manim's `BarChart` class does most of the heavy-lifting for my purposes. I only had to make a for-loop to animate the chaning values and the resulting animation is pretty nice. Here is a snippet of what I created with a puppy weight dataset:

https://youtu.be/9hykkWQaj3Y

![Bar chart race with puppy weights](./_readme_files/AnimatedBarChartWithImages.mp4)

## Installing Manim
The easiest way to install Manim is with conda, using the `conda-forge` channel:

```sh
conda install -c conda-forge manim
```

I exported my full environment into this repository, so you can just use conda to rebuild it and install all the dependencies needed, including Manim (you will need to have LaTex installed as well, so check blog post at the top for more details):

```sh
conda env create -f environment.yml
```