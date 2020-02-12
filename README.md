# LHC Assignment3: Memory, Loops, and Classes 

Question1. From assignment2 P1, reuse the code to make it user friendly, while also practicing with using functions. Write a program that does the following :
       A. Takes a single command line argument which is the path to a plain text file which is itself a newline delimited list of numbers.
       B. Read in this text file to a vector of float values (std::vector<float>). You will have to do some casting of values from the type that is read in and the float type.
       C. Define and use three functions to calculate the {sum, mean, and RMS} which take as an argument the vector of numbers that you have defined and return the value of their calculation, a single float.
       D. Print the results to the screen in an orderly manner with a description of the value that is being printed.
This is an example of a newline delimited file of floating point numbers.
  

Question2.
       A. Describe what is happening in each of the steps of assignment to the array numbers. Make a prediction of what the values would be from the array before executing the code. 
       B. After, compule and execute the code and compare if your prediction matches the output.
       C. If not, debug your understanding to determine what was incorrect in your logic. 
       D. Finally, execute the code multiple times in a row and confirm that you see the same values in the array each time. Include you printout of the code, either in the form of a screenshot or in your answer sheet.
       
       
Question3. When describing the kinematics of particles at the LHC and have the form (E,px,py,pz). In this exercise, write a piece of code in which you do the following.
       A. Define a class that represents a four-vector. Call this class FourVector
       B. Constructor : Should be implemented to force the user to initialize the members of the class
       C. Class Members : This should contain fundamental memory types that represent the energy and three- momentum (px,py,pz) of a given particle. Do not use a vector to represent energy or momentum. Call these members E, Px, Py, and Pz.
       D. Class Method 1 : Should be called and replace the contents of the full four vector with the E, px, py, and pz that you specify as arguments. Call this function SetFourVector.
       E. Class Method 2 : Should be called and return the invariant mass of the four vector (as a float). Call this function GetMass.
       F. Class Method 3 : Should be called and return the pseudorapity (η : Greek “eta”) of the four vector (as a float). Call this function GetEta
       G. Class Method 4 : Should be called with one argument which is an instance of another four vector and calculate the difference in the azimuthal angle (∆φ) between the two three-momenta of these vectors. Make sure that you take into account that the largest angular distance between two three-vectors is π. Call this function DeltaPhi.
       H. Class Method 5 : Should be called with one argument that is another four vector and calculates the difference in the pseudorapity (η) of the two four-vectors. Call this function DeltaEta.
