# Artificial Intelligence Project 1

The aim of the project is the creation of a Movie Recommendation System in Python using a world in Prolog. First of all, we process data given in the file movies_metadata.csv which provides us features of the films given. We put features in lists called literals with which we will categorize the films.Afterwards, we create a world in Prolog that will enable us to write our predicates. The file containing the predicates is uploaded with the name predicates and we use this to query the categories of the films we want. For example, "Give me all the films with 3 common genres with the Film Terminator". The queries have been written as well. In addition, some of the predicates have to do with recommendations which are based on the similarity of the films. We created five levels of similarity. For example, films with one common genre have level 1 similarity, films with 1 common genre and 1 common actor have level 2 similarity and so on. (You can see more details in the file "predicates"). Lastly, the system is upgraded to not just recommending similar movies but also movies that match user's prefereneces as the user rates films (on a 1 to 5 scale). Finally, we evaluate the system with some given metrics. We highlight that the part of evaluation and the upgrade of the system is based on given code which we processed and added additional parts. 

The project was created as part of the course "Artificial Intelligence" at School of Electrical and Computer Engineering, NTUA and the aim of this work is NOT to present it as my own research but as my approach to the problems given. We highlight that the project was implemented in Google Colab so parts of the code like the file management was done through this environment. Moreover, part of the code was given in the prompt (in Greek).

Special thanks to my fellow student, Georgios Tzamouranis (https://github.com/giorgostzamouranis) , with whom I collaborated on the implementation of this project.
