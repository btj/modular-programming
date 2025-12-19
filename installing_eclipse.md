# Installing Eclipse and FSC4J

We recommend that you download [JDK 21 from adoptium.net](https://adoptium.net/) to a location you can access later and download the Eclipse integrated development environment from [the official website](https://www.eclipse.org/downloads/packages/release/2023-12/r/eclipse-ide-java-developers). (Warning: using the Eclipse installer or any version newer or older than 2023-12 will not be compatible with FSC4J, which is necessary for this course.)

Then you have to register JDK 21 in Eclipse. 
- First open the settings menu in Eclipse
	- On Windows: go to the "Window" menu -> "Preferences"
	- On MacOS: go to the "Eclipse" menu -> "Settings".
- In the settings menu, search for "JRE" in the search bar in the top left, then click on "Installed JREs".
- If JDK 21 has not been added to this list yet, add it by clicking Add -> Standard VM -> Next -> Directory -> select where you installed the JDK -> Finish.
- Select the checkbox to the left of JDK 21 to set it to default
- Click "Apply and Close".

Once you have installed Eclipse, we recommend that you install the [Formal Specifications Checker for Java (FSC4J)](https://fsc4j.github.io/fsc4j/), that we are developing. It is a modified version of the Java Development Tools component of Eclipse that gives you feedback about the formal documentation you write. To install it, just follow [the instructions on the FSC4J website](https://fsc4j.github.io/fsc4j/#installation-instructions).

We also recommend you install [EclEmma](https://www.eclemma.org/installation.html#marketplace) to aid with testing code. It is an Eclipse plugin to easily see code coverage, i.e. what code you wrote have you also tested? To install EclEmma either drag and drop the [following link](http://marketplace.eclipse.org/marketplace-client-intro?mpc_install=264) into Eclipse, or follow the instructions on the [EclEmma website](https://www.eclemma.org/installation.html#marketplace).
