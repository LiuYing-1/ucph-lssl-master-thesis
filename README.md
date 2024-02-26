# ucph-lssl-master-thesis

This is the repository for my master's thesis at the University of Copenhagen on Longitudinal Self-Supervised Learning Methods. Hope to investigate the performance of the relatively recent self-supervision methods on longitudinal images. Hope this project turns out to be a good one. 

## Techniques

- Bootstrap Your Own Latent (BYOL) ==> Feb. 5, 2024

## Diary of the Project

- Feb. 5
    - Read the BYOL paper
    - Initiated the repository and Familiarized myself with the git commands
    - Started to implement the BYOL method

- Feb. 6
    - Be absent from the project since I got a course to attend.

- Feb. 7
    - Have a meeting with my supervisor and below are the key points.
        - Need to consider which methods should be selected.
        - Unnecessary to implement from scratch, ok to use the code from others, since the target is to evaluate.
        - Get familiar with the longitudinal data and the dataset.
        - Check the literature for the related works on the selected datasets.
    - Check the datasets and stop the implementation of BYOL for now.
    - Form the introduction of the datasets and the related works.
    - Email.

- Feb. 8
    - [x] Download the second dataset into my PC laptop.
    - [ ] Figure out the structure of the datasets and the related works.

- Feb. 9 ~ 10
    - Be absent since it is Chinese New Year.

- Feb. 11
    - [x] Post a blog for BYOL paper.
    - [x] Think about how to utilize BYOL for the longitudinal data but need help from supervisor.

        !!! The question is how to use the BYOL for the longitudinal data. BYOL itself is to train an encoder to predict the target encoder. But how to use it for the longitudinal data?

    - [x] Read the SimSIAM paper.
    - [] Read the iBOT paper.
    - [] Read the SwAV paper.
    - [] Read the DINO paper.

- Feb. 12
    - [x] Read the SwAV paper.
    - [x] Read the iBOT paper.
    - [x] Read the DINO paper.
    - [x] Methods to use for the longitudinal data.
    - [x] Understand the dataset.
    - [x] PPT.

- Feb. 12 ~ 21
    - [x] Meeting to report the progress.
    - [] Be absent to the project since I got a course to attend, and the assignment to submit.

- Feb. 21
    - [x] upload the 4DCT images to gdrive.
    - [] build BYOL
    - [] write the introduction of the methods.

- Feb. 22
    - [x] ready to see what can be done with the 4DCT images.

- Feb. 23 ~ 25
    - [x] Throw the 4DCT images into the gdrive.
    - [x] Extract the last phase of the 4DCT images for all the patients.
    - [x] Modify the BYOL method from Lucidrains to support the 3DCT images.
    - [x] Train the BYOL method on the 3DCT images.

- Feb. 26
    - [] Deep into the code and to double check whether there is something wrong with it.
    - [] Prepare the slides for the meeting.
    - [] Write the introduction of the methods to form the first draft of the thesis.
