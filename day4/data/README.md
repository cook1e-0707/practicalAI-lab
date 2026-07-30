# Day 4 Food Knowledge Data

`verified_food_knowledge.csv` contains short food-safety, food-group, and
nutrient questions and answers. Every row includes the title and URL of its
official source. The sources are limited to:

- the U.S. Food and Drug Administration (FDA);
- the U.S. Department of Agriculture Food Safety and Inspection Service
  (USDA FSIS);
- USDA MyPlate;
- the National Institutes of Health Office of Dietary Supplements (NIH ODS).

`food_knowledge_corpus.txt` is generated from those verified rows. It repeats
the records in deterministic shuffled orders so the small character-level
language model has enough text for a short training demonstration.

The two files serve different purposes:

- the CSV records the source material used to build the teaching corpus;
- the text corpus teaches tokenization, next-token prediction, training, and
  text generation.

The generated language model is not itself a reliable food-safety or nutrition
advisor. Generated text can reproduce or mix patterns without checking a
source. Verify important food information with the official source and do not
treat the lab as individualized medical advice.
