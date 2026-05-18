Pydantic

1) Define a Pydantic model that represents the ideal schema of the data

2) Instantiate the model with raw input data (usually a dictionary or JSON-like structure)

Pydantic will automatically validate => validated pydantic object

If data doesn't meet the model's requirements => Validation Error

3) Pass the validated object model to functions or use it throughout your codebase


## Pydantic Uses

Better organization of related data (eg: vitals, address, insurance)

Reusability: Use vitals in multiple models (eg: Patiend, MedicalRecord)

Readability: Easier for developers and API consumers to understand

Validation: Nested models are validated automatically - no extra work needed