# ADS-508 – Cloud Computing
### Completed: 04/14/2024
## Authors:
•	Jesse Gutierrez

•	Sowmiya Kanmani Maruthavanan

•	Verity Pierson


**Company Name**:  Velocity Vision

**Company Industry**:  Law Enforcement

**Company Industry**: 9,000

## Methods

•	Data Exploration (EDA)

•	Pre-Processing

•	Data Visualization

•	Modeling

## Technologies

•	Python (AWS SageMaker)

•	AWS (SageMaker, Athena, S3)

## Abstract

Collaborating with local law enforcement to address speed related car accidents at a high-risk intersection lacking police presence. We aim to develop a computer vision model that regulates traffic in real-time, minimizing accidents and enhancing overall road safety.

## Problem Statement

It is our company’s commitment to the community and the challenges at this high-risk intersection, with its pressing issue of speed-related car accidents, demands urgent attention. Historically, the absence of continuous police presence at this location has resulted in an alarming increase in accidents, posing a significant threat to public safety. Our company, with a proven track record in developing innovative solutions, recognizes the need to address this issue by leveraging our expertise in data science and technology.

The need for an automated system, such as a computer vision model, becomes evident as we aim to regulate traffic seamlessly and reduce the frequency of accidents. By proactively addressing this critical problem, our company seeks to build upon its legacy of creating impactful solutions that contribute to community well-being. The intersection’s history of high mortality rates underscores the urgency of our mission, emphasizing the importance of deploying cutting-edge technologies to enhance road safety and make a lasting positive impact on the local community.

## Goals

A list of the three to five outcomes that will come as a result of this design. Defining goals helps others understand what success of this project will look like.
Optimize traffic flow – Calculates traffic density in real-time by analyzing the number and speed of vehicles passing through the intersection.
Minimize speed-related accidents - Reduce the number of accidents caused by speeding vehicles at high-risk intersections.
Enhanced Law enforcement - Enhance the effectiveness of enforcing speed limits and other traffic regulations, particularly in areas lacking police presence.

## Non-Goals

What are you intentionally not doing or solving with this project? Defining three to five non-goals helps limit the scope of your project and prevents feature creep.

While we would love to expand the model’s capabilities, the initial focus will be on accurately identifying vehicles that are exceeding the posted speed limit. For now, this will not include:

•	Detection of other traffic violations

•	Detection of service vehicles (ambulance, firefighters, and law enforcement)

•	Detection of construction or weather conditions that may influence speed

•	Detection of pedestrians or cyclist

•	Detection of stolen vehicles or license plates

## Data Sources

Our data files will be stored in a public S3 bucket on AWS service due to the number of images in our selected data sources. This will in turn communicate with AWS SageMaker.

•	[Vehicle Speed](https://www.kaggle.com/datasets/tanishqdublish/vehcile-speed-data)

o	Date: 2021

o	Location: Czech Republic

o	Observations: 5,973

•	[Vehicle Type](https://www.kaggle.com/datasets/jessicali9530/stanford-cars-dataset)

o	Observations: 16,185

•	[License Plate Identification](https://www.kaggle.com/datasets/mohamedgobara/plate-license-recognition-dataset)

o	Observations: 39 classes

o	Observations: 4,042

•	[Upd. License Plate Identification](https://www.kaggle.com/datasets/fareselmenshawii/large-license-plate-dataset)

o	Observations: 26,900

•	[Traffic Signals](https://www.kaggle.com/datasets/pkdarabi/cardetection)

o	Observations: 4,969


## References

AWS.com, (2024). Use Amazon SageMaker Built-in Algorithms or Pre-trained Models. Retrieved from https://docs.aws.amazon.com/sagemaker/latest/dg/algos.html


