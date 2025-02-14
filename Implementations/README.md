# Implementations

work-in-progress

This page provides a list of implementations based on the OGC Training Data Markup Language for Artificial Intelligence (TrainingDML-AI) Standard. These implementations are designed to support the adoption and utilization of the TrainingDML-AI Standard across different platforms and applications. They offer a variety of tools, libraries, and APIs that enable users to work with training data in a standardized and interoperable manner. Whether you need to manage, annotate, share, or analyze training data for AI purposes, these implementations provide the necessary resources and functionalities to support your workflow.

## Contribution

If you have any implementations or contributions related to TrainingDML-AI, we welcome pull requests to update this page and add your contributions. You can provide more detailed information about your implementation in a subfolder. Please provide your email address so that we can contact you for page updates or any questions.

## PyTDML Implementation

[PyTDML](https://github.com/TrainingDML/pytdml) is a pure python parser and encoder for training datasets based on OGC Training Data Markup Language for AI standard.

Additionally, PyTDML is currently in the process of designing and implementing a pipeline service that enables the entire workflow from sample loading to sample consistency handling, sample transformation, and iterative training. We have designed user-friendly APIs that adhere to the OGC TrainingDML-AI Standard. With these APIs, users can automate the process of feeding TrainingDML-AI-encoded datasets into deep learning frameworks such as PyTorch, TensorFlow, and others.

## TrainingDML-AI STAC Extension Implementation

[TrainingDML-AI STAC Extension](https://github.com/TrainingDML/trainingdml-ai-extension) is designed as an extension to the SpatioTemporal Asset Catalog (STAC) specification. It builds upon the STAC specification and specifically addresses the requirements for geospatial machine learning training data and introduces additional fields and metadata concepts to formalize the information model of training data within the STAC framework.The extension expands upon the core STAC specification to accommodate the specific needs of training data, enabling interoperability and facilitating effective management and utilization of geospatial machine learning training datasets within the STAC ecosystem.

## LuojiaSet TrainingDML-AI Server Implementation

[LuojiaSet](http://58.48.42.237/luojiaSet) has implemented the TrainingDML-AI Standard and utilized it to encode the data within the LuojiaSet dataset and customized code was developed to prototype the use cases of dataset.

This implementation allows for retrieving the complete encoded content of the corresponding dataset by using the dataset record ID.
