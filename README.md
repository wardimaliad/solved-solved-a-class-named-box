Download Link: https://assignmentchef.com/product/solved-solved-a-class-named-box
<br>
<p class="ui header product-top-header" title="The following code is for a class named Box Solution">The following code is for a class named Box. The class Box includes a constructor method Box, and a method getVolume().

class Box {

double width;double height;double depth;

// This is an empty constructorBox() {;}

Box(double w, double h, double d) {width = w;height = h;depth = d;}

void getVolume() {System.out.println(“Volume is : ” + width * height * depth);}}

For your assignment you are to develop a java class named MatchBox. Your class MatchBox must extend the class Box and in addition to the attributes width, height, and depth that are defined in the class Box, MatchBox must add a new attribute weight. The getVolumemethod must both report the values of width, height, depth, and weight, but must also calculate and report the volume by multiplying height by width by depth. The class MatchBox must also add the method calculateWeight() that will calculate weight based upon the volume assuming that the volume is a quantity of water which weighs .03611 pounds per cubic inch. Also method calculateWeightshould show the result like this: weight of MatchBox is X.

For example a car class can inherit some properties from a General vehicle class. Here we find that the base class is the vehicle class and the subclass is the more specific car class. A subclass must use the extends clause to derive from a super class which must be written in the header of the subclass definition. The subclass inherits members of the superclass and hence promotes code reuse. The subclass itself can add its own new behavior and properties.

Your new class must include a main method that creates a new MatchBox object, calls the getVolume method and reports the results by printing the following items to the screen (where the X is replaced by the calculated value) For your assignment, assume that the value of width is 5, height is 10, and the depth is 3. The output should look like the following with X replaced with the appropriate calculated value.

width of MatchBox is Xheight of MatchBox is Xdepth of MatchBox is Xweight of MatchBox is XVolume is: X