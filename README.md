# Bakers Percentage
This console app calculates total amount of ingredients needed for different types of bread, based on target weight of dough (vs. volume, for more consistent results). It uses "Baker's Percentage" for each available bread type, where each ingredient is calculated as a percentage of the total Flour. 

Bread models are derived from the base model class and methods, with polymorphic properties for individual ingredient percentages. It is the MVC and interface-based version of my Baker's Percentage Blazor component and API.

## Sample Output
<img src="https://user-images.githubusercontent.com/83464025/177398099-cda76add-710c-4258-b5a5-2a5f94460e79.png">

## Instructions

To clone and run the program on your local system, do the following:

- create a new folder, such as "test", then run these commands
- > cd test
- > git clone https://github.com/hellums/bakers.git
- > cd bakers
- > dotnet run

You can also use Visual Studio to run from the IDE by loading the bakers.sln file in that folder, after cloning

## Code Louisville Requirements List
- [X] Project includes a [README file](https://github.com/hellums/bakers/blob/root/README.md) that explains the following:
  - [X] A one paragraph or longer description of what your project is about
  - [X] Any special instructions required for the reviewer to run your project
- [X] Implement a [“master loop”](https://github.com/hellums/bakers/blob/0a81141147874d55a5204060c133c755710801c0/bakers/Controllers/PercentageController.cs#L11) console application, including choosing to exit the program
- [X] Create at least [one class and object instance](https://github.com/hellums/bakers/blob/0a81141147874d55a5204060c133c755710801c0/bakers/Models/PercentageModel.cs#L1) with populated data used in the application
- [X] Create an additional [class which inherits one or more properties](https://github.com/hellums/bakers/blob/0a81141147874d55a5204060c133c755710801c0/bakers/Models/PercentageModel.Ciabatta.cs#L3) from its parent
- [X] Create and call at least [3 functions or methods](https://github.com/hellums/bakers/blob/0a81141147874d55a5204060c133c755710801c0/bakers/Views/PercentageView.cs#L47), at least one of which [returns a value used](https://github.com/hellums/bakers/blob/0a81141147874d55a5204060c133c755710801c0/bakers/Views/PercentageView.cs#L45) in the application
- [X] Create a [dictionary or list](https://github.com/hellums/bakers/blob/0a81141147874d55a5204060c133c755710801c0/bakers/Views/PercentageView.cs#L10), populate it with several values, [retrieve at least one value](https://github.com/hellums/bakers/blob/0a81141147874d55a5204060c133c755710801c0/bakers/Controllers/PercentageController.cs#L13), and use it in your program
- [X] Implement a [log that records errors](https://github.com/hellums/bakers/blob/0a81141147874d55a5204060c133c755710801c0/bakers/Models/Logger/Logger.cs#L16), invalid inputs, or other important events and writes them to a text file
- [X] Build a [conversion tool](https://github.com/hellums/bakers/blob/0a81141147874d55a5204060c133c755710801c0/bakers/Models/PercentageModel.cs#L20) that converts user input to another type and displays the results
- [X] Create [3 or more unit tests](https://github.com/hellums/bakers/blob/0a81141147874d55a5204060c133c755710801c0/BakersTest/PercentageModelTest.cs#L4)
