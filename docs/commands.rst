Commands
========

The Makefile contains the central entry points for common tasks related to this project.

Syncing data to S3
^^^^^^^^^^^^^^^^^^

* `make sync_data_to_s3` will use `aws s3 sync` to recursively sync files in `data/` up to `s3://This project is an AI assitant, my copy/ attempt to build a siri/alexa/google assistant that i can delegate responsibilities to and can get things done. For the first stage, I want to builda research assistant that can I ask ask about a paper ) and it will be a ble to get the task done and communicate back via a TTS model1/data/`.
* `make sync_data_from_s3` will use `aws s3 sync` to recursively sync files from `s3://This project is an AI assitant, my copy/ attempt to build a siri/alexa/google assistant that i can delegate responsibilities to and can get things done. For the first stage, I want to builda research assistant that can I ask ask about a paper ) and it will be a ble to get the task done and communicate back via a TTS model1/data/` to `data/`.
