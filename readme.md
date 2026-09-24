aloha


In this assignment, I learned the basic Git and GitHub workflow. I practiced creating and cloning a repository, tracking changes with `git add` and `git commit`, and pushing local commits to a remote GitHub repository. I also learned how local branches such as `main` relate to remote branches such as `origin/main`.

I practiced Git branch management by creating the `for_fun` branch, switching between branches, and merging branches. I also learned how to use `git log` to inspect commit history and how to check out an earlier commit. Checking out an old commit helped me understand the detached HEAD state and showed me that Git allows me to revisit an earlier snapshot without deleting newer commits.

I also learned how to manage a Python environment for a machine learning project. I used Conda and pip to work with Python packages such as PyTorch, torchvision, and Transformers/Hugging Face. During this process, I learned that the Python executable and pip installation can come from different environments, so commands such as `which python` and `python -m pip --version` are useful for checking which environment is actually being used.

For the machine learning part, I used a pretrained ResNet-18 model to run inference on the MNIST test dataset. MNIST contains 28x28 grayscale images, while ResNet expects larger three-channel images, so I resized the MNIST images to 224x224 and converted them to three channels before passing them into the model. The pretrained model was not fine-tuned on MNIST, so the accuracy was low (16.14%), but this experiment helped me understand the difference between using a pretrained model directly and training or fine-tuning a model for a specific task.

Finally, I learned the importance of keeping a repository clean. I used `.gitignore` to prevent datasets, cache files, and other unnecessary files from being committed. Overall, this assignment helped me understand how Git version control, Python environments, and machine learning workflows fit together in a practical project.