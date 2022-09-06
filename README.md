# Tiny ML benchmark

## 1. Inference time

Inference time is shown to the serial monitor. This time is captured every time a new command is spoken. 

![img_5.png](img_5.png)

For the sample use case the tame taken for each inference is ~72 ms.

## 2. Static Size and code size

To capture the code size and static 
1. First Enable verbose ouput in the Preferences Pane. 

![img_1.png](img_1.png)

2. Then after compliling the sketch we can see the command to be executed to check the code size and static data size.

![img_2.png](img_2.png)

3. Running this command will give the code size and static size.

![img_3.png](img_3.png)

4. Dynamic memory consumption is also captured during sketch compilation.

![img_4.png](img_4.png)

