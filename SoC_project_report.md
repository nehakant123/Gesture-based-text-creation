***GESTURE BASED HAND RECOGNITION : SOC REPORT***

**Initial Insights**

My project for the Summer of Code(SoC) was focused on gesture-based hand recognition. I chose this topic because of my deep curiosity about how advanced technologies, 
such as autonomous vehicles and gesture-controlled devices, operate. For instance, companies like Tesla have developed incredible automated cars, and gesture-based filters to
enhance our photos, while recommendation systems personalise our experiences.
This project provided me with a deeper understanding of the mechanisms behind these innovations, answering many questions that have intrigued me about how things work. 
By exploring gesture-based hand recognition, I gained insights into the intersection of computer vision, machine learning, and real-world applications.
Let me take you through my project journey.

**Understanding the basics**

I started my journey by learning some basics of python. The basics included learning about different libraries for instance numpy , matplotlib, math and many more.I learnt how 
to plot different kinds of graph using matplotlib library.Our first assignment was mainly focused on brushing up our coding skills.

**Unfolding the Project Story: From Start to Finish**

Then we moved forward and learned about neural networks. Neural networks were an important part of our journey. I learned about how neural networks behave and how two layers are 
connected to each other.I also learned about different type of activation functions and how they affect our results.Then comes the most important part of Neural Networks
backpropagation.

Backpropagation is a fundamental algorithm used in training neural networks. It involves calculating the gradient of the loss function with respect to each weight by the chain
rule, iterating backward from the output layer to the input layer. This allows us to adjust the weights to minimise the error between the predicted output and the actual output.

Then we learned about CNNs (Convolutional Neural Networks). CNNs reduce the number of trainable parameters by using different types of pooling layers, which makes them suitable for
handling large size datasets. They can also extract features from images, which helps in learning local patterns. Our Week 3 assignment was mainly focused on this aspect and required us to create different CNN models for various datasets.

Then we moved on to learning the most exciting aspect of our project that is using the OpenCV and MediaPipe libraries to capture real-time images. I was so interested that I 
created various programs, such as FaceMesh and gesture-based volume control, which eventually contributed to my final project. Our week 4 and week 5 was mainly focused on this 
part. In week 5, we tackled tasks such as drag-and-drop functionality, gesture-based brightness control, and more.

Finally, after learning many new and exciting things, we reached week 6, the culmination of our journey. In this week, I was required to implement the knowledge gained over the 
past five weeks and create a gesture-based handwritten digit recognition model.

**Model Framework and Capabilities**

To enhance the visual experience of utilising various colour brushes, I incorporated different template headers to give a more engaging user interface.I included an eraser to 
remove any unnecessary parts. The template header features a volume control option, which allows users to adjust the system volume through gestures. Additionally, a sun icon is 
provided to manage screen brightness via gestures. To enhance user experience, I incorporated a visual level bar that displays the current brightness level. The header dynamically
changes according to the functionality selected by the user.I used three distinct CNN models to generate predictions, and then aggregated the results from these models. 
The final prediction was determined by selecting the number with the highest count among the results.

**Roadblocks and Workarounds**

Throughout the project, I faced several challenges, including finding optimal libraries for my system, developing a level bar for brightness control, and troubleshooting 
various errors. To overcome these obstacles, I analysed various open-source GitHub repositories and continuously refined my code.

**End of Journey: Key Takeaways**

In conclusion, this project on gesture-based hand recognition has been a remarkable journey through advanced concepts in computer vision and neural networks. By integrating 
real-time image processing with neural network models, I was able to develop a system that not only recognises hand gestures but also translates them into meaningful actions, 
such as controlling volume and brightness.

The project allowed me to apply and expand my knowledge of Convolutional Neural Networks (CNNs) and OpenCV, transforming theoretical concepts into practical applications. 
Implementing different CNN models and using gesture-based interfaces has provided valuable insights into the challenges and possibilities of interactive systems.

Despite encountering several roadblocks, such as optimising libraries and developing user interface features, the experience has been highly rewarding. By continuously
iterating and refining my approach, I successfully addressed these challenges and achieved the project's goals.

This project has significantly enhanced my understanding of machine learning and computer vision, demonstrating the potential of gesture-based technology in creating intuitive 
and interactive user experiences. Moving forward, I am excited to explore further applications and innovations in this field, building on the foundation laid by this project.
