# HW_14_Bioinformatic_functions

## Description
BiologicalSequence is a base class for working with biological sequences.
NucleicAcidSequence is a base class for nucleic acids (DNA and RNA) and implements the complement method.
DNASequence and RNASequence are inherited from NucleicAcidSequence. DNASequence implements the transcribe method and RNASequence implements the translate method.
AminoAcidSequence is designed to work with amino acid sequences and includes a method for calculating molecular weight.
FastQFilter is designed for filtering FastQ files by specified criteria using Biopython capabilities.

## Troubleshooting

If you encounter any issues while using this toolkit, consider the following troubleshooting steps:

1. **Check Dependencies**: Ensure that you have all the required dependencies installed. The success of the toolkit's functions may depend on external libraries or modules.

2. **Verify Module Imports**: Double-check that you are correctly importing the required modules from the `scripts` directory. Make sure the module files exist and are accessible.

3. **Function Parameters**: Review the documentation for each function to ensure you are providing the correct parameters. Incorrect inputs may result in errors.

4. **Error Messages**: Pay attention to any error messages or exceptions that are raised. They can provide valuable information about what went wrong.

5. **Open an Issue**: If you encounter a persistent problem that you cannot resolve, consider opening an issue on the project's GitHub repository. Provide details about the issue, including the specific function you were using, the input data, and any error messages.

## Feedback

Your feedback is important for the improvement of this toolkit. If you have suggestions, feature requests, or any other feedback, please feel free to reach out. You can provide feedback through the following channels:

- Open an issue on the project's GitHub repository to report bugs or request features.
- Send an email to the project's author to provide feedback or ask questions.
