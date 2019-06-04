# HillModel
In 2006, Dr. Holmes published an article in the series “Teaching From Classic Papers” in the journal Advances in Physiology Education. The article describes the use of a MATLAB implementation of the model described in A.V. Hill’s classic 1938 paper to allow students to simulate experiments similar to those Hill performed. By performing appropriate experiments, students can see how Hill arrived at his conclusions about the relationship between muscle force, muscle velocity, and heat production – conclusions that set the stage not only for Hill’s influential model of interacting contractile and series elastic elements, but also for Huxley’s crossbridge model.

If you wish to refer to the simulations, please cite the Advances in Physiology article, which is available free through a link from PubMed: [Holmes JW. Teaching from classic papers: Hill’s model of muscle contraction. Adv Physiol Educ 30(2):67-72, 2006](http://www.ncbi.nlm.nih.gov/pubmed/16709736)

## hill.m
This is the MATLAB function that simulates the response of the Hill model to a prescribed length input.

## hilldemo.m
This is a MATLAB m file that demonstrates how to use the function by creating length input arrays and feeding them to the function.

## hillinteractive.m
This is a MATLAB program for the programming-averse. It uses a very simple graphical interface to let the user design length inputs to the Hill simulation as an alternative to the method shown in hilldemo. Engineering students will not need this...
