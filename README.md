# Object-Detection-with-PyTorch-in-Java

Basically I just followed a tutorial to run PyTorch in Java. Followed [this](https://towardsdatascience.com/implement-object-detection-with-pytorch-in-java-in-5-minutes-c3ba5769e7aa) tutorial which does a great job getting you up and running.

## Run the code
1. Open the Windows Powershell and move into your project directory. 

2. run `./gradlew build` to build the project from Gradle.

Then run [App.java](https://github.com/yeoffrey/Object-Detection-with-PyTorch-in-Java/blob/master/src/main/java/com/geoffreybelcher/app/App.java).

Output will have an error, but should say something like:  
`[
	class: "person", probability: 0.99727, bounds: [x=0.302, y=0.109, width=0.466, height=0.884]
]`

You can change the image shown by changing the varibale `url` in [App.java](https://github.com/yeoffrey/Object-Detection-with-PyTorch-in-Java/blob/master/src/main/java/com/geoffreybelcher/app/App.java).
`String url = "https://geoffreybelcher.com/images/geoff-skate.png";`
