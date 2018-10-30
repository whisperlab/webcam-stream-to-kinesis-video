# webcam-stream-to-kinesis-video

## Overview

This is a serverless web application for streaming webcam feed from a browser to [Amazon Kinesis Video Streams](https://console.aws.amazon.com/kinesisvideo) and [Amazon Rekognition Video](https://docs.aws.amazon.com/rekognition/latest/dg/streaming-video.html).

This project was primarily adapted from: https://github.com/brain-power/Brain-Power-Amazon-Fidgetology

AWS Technologies used:
* Kinesis Video Streams
* Kinesis Data Streams
* API Gateway
* Lambda
* S3
* CloudFormation

## Deployment

1. Clone the repo to a local directory

  ```sh
  git clone https://github.com/matwerber1/webcam-stream-to-kinesis-video
  ```

2. Open template.yaml and edit the CloudFormation parameters as needed. 

3. Run the deployment script
  ```sh
  ./deploy.sh
  ```


## Components

### Web Dashboard App

The client dashboard app allows users to stream a webcam feed to [Amazon Kinesis Video Streams](https://console.aws.amazon.com/kinesisvideo).