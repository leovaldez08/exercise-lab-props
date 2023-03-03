![Logo](https://s3.ap-south-1.amazonaws.com/kalvi-education.github.io/front-end-web-development/Kalvium-Logo.png)

### Learning Goals:
The aim of this exercise is to practice and understand the concept of `props`.
You are free to solve this exercise by any approach - either `class-based` or `functional-based`.

### Steps to follow:

1. Clone this repository.

2. On your terminal go inside `exercise-lab-props-boilerplate` directory and use the following command: `npm install`.This command install's all the packages to your system that this project is using.
Here is a link to get a better understanding of what and how exactly the above command works.

[What is npm install](https://www.stackchief.com/tutorials/npm%20install%20%7C%20how%20it%20works)

3. Once everything is ready, you can type `npm start` -> inorder to run the application. You should be able to see a server running and see the output as shown below:

![jsx](https://s3.ap-south-1.amazonaws.com/kalvi-education.github.io/front-end-web-development/exercise-lab-jsx.png)

4. Notice one thing - the data is already given to you inside -> `images` folder. Inside `components/Data.js` component, you can see that the image stored in `images` folder is being imported to this component. You can use this `Data.js` component for fetching images.


### Task:

Your task is to complete the code for `Image.js` component. ( You can complete this by using any method - class-way or functional-way )
Now, if you notice your `App.js` component, you will observe that `<Image data={Data}></Image>` is being rendered at last. So, this is the point, where all the data is being passed as a prop to your `Image.js` component. 
Your task is handle this data, and return all the images.

your final output should look something like this:

![props](https://s3.ap-south-1.amazonaws.com/kalvi-education.github.io/front-end-web-development/props-exercise-react.png)
