# Multi-level-Color-Image-Segmentation-using-Differential-Evolution
Population initialisation ,Evaluation, Mutation, CrossOver and the segmented image 
# Flowchart
<img width="546" alt="image" src="https://user-images.githubusercontent.com/94094997/154531724-fba5f4b6-a67b-4047-9281-be305bd593b4.png">

# DE Steps
1)Input:
    -The input image to be segmented
    -Size of the population NP
2)Population initialization:
    -Generate a population P with the given NP
3)Evaluation:
    -Calculate the fitness value
4)Mutation :
    -Selecting three random numbers (a, b, c) to create a mutant vector
5)Crossover: 
    -Recombine the mutant vector with P
6)Output:
    -The segmented image
# DE Steps(Flowchart)
<img width="709" alt="image" src="https://user-images.githubusercontent.com/94094997/154532788-3ea56486-2933-44d6-8f93-cc9a2505873f.png">

# Implementation

# Population generation
Rand () function is used to get random pixel value from the image.

# Fitness Calculation

Variance for n- cluster is found. (Inter Cluster Variance)

<img width="210" alt="image" src="https://user-images.githubusercontent.com/94094997/154534045-92360636-3516-4d6d-bb0e-2aece1ca524e.png">

# Differential Evolution

<img width="898" alt="Screenshot 2022-02-17 at 12 23 50 PM" src="https://user-images.githubusercontent.com/94094997/154536518-8bf9204f-08a7-4fe9-9f91-6054742c9533.png">

# Cluster Generation

<img width="893" alt="Screenshot 2022-02-17 at 12 25 24 PM" src="https://user-images.githubusercontent.com/94094997/154536777-98907580-484a-4820-a273-993cd21f596e.png">

