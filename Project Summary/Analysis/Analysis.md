{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "a8fbc24a-175b-42f2-8319-69bc38c51e65",
   "metadata": {},
   "source": [
    "# Analysis\n",
    "\n",
    "## Data Processing\n",
    "\n",
    "- Loaded employee performance dataset.\n",
    "- Examined dataset structure and feature information.\n",
    "- Checked for missing values.\n",
    "- Verified data quality.\n",
    "- Encoded categorical variables using Label Encoding.\n",
    "\n",
    "## Exploratory Data Analysis\n",
    "\n",
    "The following analyses were performed:\n",
    "\n",
    "### Performance Rating Distribution\n",
    "\n",
    "Most employees belong to Performance Rating 3 category.\n",
    "\n",
    "### Department Analysis\n",
    "\n",
    "Employee performance varies across departments.\n",
    "\n",
    "### Overtime Analysis\n",
    "\n",
    "Employees working overtime showed performance patterns different from employees without overtime.\n",
    "\n",
    "### Environment Satisfaction Analysis\n",
    "\n",
    "Higher environment satisfaction is associated with better performance ratings.\n",
    "\n",
    "### Work-Life Balance Analysis\n",
    "\n",
    "Employees with better work-life balance generally achieve higher performance ratings.\n",
    "\n",
    "## Machine Learning Analysis\n",
    "\n",
    "Two models were developed:\n",
    "\n",
    "1. Decision Tree Classifier\n",
    "2. Random Forest Classifier\n",
    "\n",
    "### Model Performance\n",
    "\n",
    "| Model | Accuracy |\n",
    "|---------|---------|\n",
    "| Decision Tree | 89.17% |\n",
    "| Random Forest | 95.00% |\n",
    "\n",
    "Random Forest achieved the best performance and was selected as the final model."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "eab00b50-8797-4752-93a7-337eabab09c7",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python [conda env:base] *",
   "language": "python",
   "name": "conda-base-py"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.12.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
