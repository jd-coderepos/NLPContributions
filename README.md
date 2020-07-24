
# Pilot-data
Pilot data annotations for the NLPContributions Model.

The repository is organized as follows:

    README.md                            
    [task-name-folder]/                                # machine-translation, named-entity-recognition, question-answering, relation-classification, text-classification
        ├── [article-counter-folder]/                  # ranges from 0 to 9 since we annotated 10 articles per task
        │   └── research-problem.json              # `research problem` mandatory information unit in json format
        │   └── model.json                         # `model` information unit in json format; in some articles it is called `approach`
        │   └── ...                                # there are 8 main information units in all and each article may be annotated by 3 or 6
        │   └── triples/                               # the folder containing information unit triples one per line
        │   │   └── research-problem.txt               # `research problem` triples (one research problem statement per line)
        │   │   └── model.txt                          # `model` triples (one statement per line)
        │   │   └── ...                                # there are 8 main information units in all and each article may be annotated by 3 or 6
        │   └── ...                                    # there are ten articles annotated for each task, so this repeats nine more times
        └── ...                                        # there are five tasks selected overall, so this repeats four more times

# Citation
Coming soon...
