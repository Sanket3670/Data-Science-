# Data-Science
Problem Statement:
Develop a scalable and accurate solution to process lab reports with the objective of extracting all lab test
names, their corresponding values, and reference ranges. Use the provided dataset of lab report images to
build logic/model.

The logic must be implemented in Python and deployed as a Fast API service. The API should expose a
POST endpoint /get-lab-tests that accepts an image file as input and returns the extracted lab test data in a
structured JSON format.
Dataset link: https://drive.google.com/file/d/1LzG7oJ-cqGHK9KbwXnWfkWgnQ3xi8Cr9/view?usp=sharing
*lab_test_out_of_range must be calculated after obtaining the bio_reference_range, it’s a Boolean value describing if
the test lies outside the normal range.
*is_success (Boolean flag) - Returns True if the API call is executed successfully.
