# Notes-on-Classification

Loss Functions for multi-class and multi-label

Multi-class multi-label problem:
More than 2 classes and each case can get any and multiple classes the same time.
Loss function: BCEWithLogitsLoss (with no sigmoid() or softmax())

Single-label Multi-class problem
More than 2 class and each case can get a single one.
Loss function: CrossEntropyLoss (without softmax)
