# docetl_examples
This repo will have examples of docetl usage.
please ensure to create a .env file in the root and add OPENAI_API_KEY as below

OPENAI_API_KEY = < mention your openai key >

#### How to use docetl to extract topics from youtube video

This use case example uses two components in the repo

1. ./data/video_ids.json  - In this file I specified the id of the youtube video that needs to be analyzed
2. ./pipelines/youtube_extraction_pipeline.yaml - This contains the declarative opearations to extract the topics from youtube

To run this pipeline:

_docetl run ./pipelines/youtube_extraction_pipeline.yaml_
