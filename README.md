# Judge a book by its cover. Generative approach.


This  project  is  an  example  of  generative  art  and  design  application  in  publication graphic design. It shows how programming may be applied in a book covers generation. The work combines such fields of Computer Science as Natural Language Pro-cessing (processing text data to get its structure and features), Algorithms and Data Structures (representing and working with a tree data structure), and Data Visualization (generation of cover elements).  All covers are generated for Artemis Fowl – a series of novels by Eoin Colfer.  We propose three approaches to create elements for book covers: from more data-driven and less generative to more generative and less data-driven.

The idea was inspired by Stefanie Posavec’s talk about what ‘handmade’ means in regards to data visualization and how data illustrators usually perform complicateddata processing without writing a simple line of code.


## Approach 1

The first approach shows how two characteristics extracted from a book – its structure and a text polarity score – are used to create a book cover in a data-driven way. Two main elements are a graph generated with a radial tree approach and a background gradient image.

!["Artemis Fowl" book covers - approach 1](images/Approach1.png)


## Approach 2

A data-driven approach with noise added to show the book data. A book structure is displayed in a spiral plot with book chapters as main visual components and paragraphs along with their sentences as the data that creates visual noise in a graph.

!["Artemis Fowl" book covers - approach 2](images/Approach2.png)


## Approach 3

a generative approach to the book cover creation process. As a basis for generation, we chose a Peter de Jong attractor. Such text features as average word length, average sentence length, and the average number of sentences in a paragraph are used as the attractor parameters.

!["Artemis Fowl" book covers - approach 3](images/Approach3.png)


## Prerequisites 

To install all the required packages run the following command:

```
pip install requirements.txt
```

## Conclusion

All book covers are available in [Artemis Fowl book covers](https://drive.google.com/open?id=1lEiQq-F0_XQqbo4DqrS-58wqXz8KKti2).

To sum up, using generative art to create publications design broaden possibilities of what can be illustrated. Moreover, it gives more flexibility and adjustability to creating visual based on distinctive inputs. 
