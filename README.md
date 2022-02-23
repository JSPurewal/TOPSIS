# Topsis

Topsis(Technique for Order Preference by Similarity to Ideal Solution):
Of the numerous criteria decision-making (MCDM) methods, TOPSIS is a practical and useful technique for ranking and selecting a number of possible alternatives by measuring Euclidean distances. TOPSIS, is a simple ranking method in conception and application. The TOPSIS method based on information entropy is proposed as a decision support tool in many fields. The purpose of this methodology is to first arrive at an ideal solution and a negative ideal solution, and then find a scenario which is nearest to the ideal solution and farthest from the negative ideal solution.


## Usage for Topsis.py

```bash
python Topsis.py <input_filename.csv> "<Weights>" "<Impacts>" <output_fileName.csv>
```
The weights and impacts must be string and must be comma-separated. 
Input file must contain the first column as Product or Model name. Rest all columns must be numeric.
The number of weights and impacts must be same as the number of numeric columns.
There must be atleast 2 numeric columns.

Eg.
```bash
python Topsis.py input_data.csv "1,1,2,1" "+,-,-,+" result.csv
```