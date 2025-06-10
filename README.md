**Road Scenario Extraction Using Natural Language Query**

This study demonstrates how scene graphs can be used to find a specific clip using natural language queries from a collection of road scene clips. A framework has been developed to locate the desired clip from a pool of road scene clips. This framework includes scene graph generation, understanding the scene using a resultant scene graph function, summarizing the information from the resultant scene graph function, and finding the cosine similarity between the summarized information and the natural language query provided by the user. The framework was applied to locate the required clip from the collection of clips. The results highlight the need for improvement in summarization model, object detection and to decrease number of frames between first and last frame from which resultant scene graph data is extracted.

Below is the framework of the project:
Here to convert road scene video frame into scenegraph a tool call roadscene2vec(https://github.com/AICPS/roadscene2vec) is use.

In first step frames of the video clip is converted into scenegraph
![Screenshot 2025-06-11 050033](https://github.com/user-attachments/assets/d06d1358-5a52-494d-ae18-973bc1fa5a24)
