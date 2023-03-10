![PrediFy](https://user-images.githubusercontent.com/97115854/223779164-c685e5a1-cdf5-4f14-8669-082b8aed5275.png)
- [Project summary](#project-summary)
  - [Problem we are trying to solve](#problem-we-are-trying-to-solve)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [IBM AI service(s) used](#ibm-ai-services-used)
  - [Other IBM technology used](#other-ibm-technology-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Solution demo video](#solution-demo-video)
  - [Project development roadmap](#project-development-roadmap)
- [Additional details](#additional-details)
  - [How to run the project](#how-to-run-the-project)

## Project summary

### Problem we are trying to solve

More than a quarter of the world’s population — 2.2 billion people —  experience the ill effects of vision disability out of which, 1 billion cases could have been prevented or have been left unaddressed, as indicated by the first World Vision Report published by the World Health Organization (WHO) on October 8, 2019. 

These 1 billion people include those with moderate or extreme distance vision impairment or blindness due to unaddressed refractive error (123.7 million), unaddressed presbyopia (826 million), cataract (65.2 million), glaucoma (6.9 million), corneal opacities (4.2 million), diabetic retinopathy (3 million), and trachoma (2 million).

India is known as the Blind Capital of the world. At 8 million, India has the world’s largest blind population. Nearly half of it was preventable. In India, 41% of children (under 18 years) are estimated to  need visual correction but are not corrected. About 42% of workers , 42% of drivers and 45% of elderly people are similarly placed in remote areas where they don’t have access to right specialists and tools.

![image](https://user-images.githubusercontent.com/97115854/223938851-57130b3f-2918-467e-9a5e-dbaced3a44bd.png)

### Our idea

EyeNetics is an AI enabled app that can predict Diabetic Retinopathy and Glaucoma at a early stage by using just the retinal scan of the patient. 

The working of this app is fairly simple: all you need to do is enter some information of the patient and the retinal scan and then the app would determine whether the patient is having Diabetic Retinopathy or Glaucoma or not using the ML Model linked to it. The app doesn’t need the retinal scan to be from any high end slit lamp with a imaging system. It can work with the retinal scan from any low cost slit lamp as it uses a ML Model and Artificial Neural Network to recognize patterns on the basis of which it predicts.
The app uses a database of over 32000 retinal scan to recognize patterns of visual impairment diseases and the accuracy of the prediction of this app is way more than the accuracy of prediction by an ophthalmologist making our app very reliable.
With this app we plan to impact nearly 1 billion people including ophthalmologists and want to revolutionize vision correction with AI. Our target population are mainly Ophthalmologists practicing in remote areas with less access to high-end imaging system. We want to empower these Ophthalmologists with AI and want to uplift their level of service by simultaneously decreasing their cost as they no longer need to buy expensive slit lamp which would eventually decrease their fees to the patient making vision correction affordable and accessible for all. 

## Technology implementation

### IBM AI service(s) used

_INSTRUCTIONS: Included here is a list of commonly used IBM AI services. Remove any services you did not use, or add others from the linked catalog not already listed here. Leave only those included in your solution code. Provide details on where and how you used each IBM AI service to help judges review your implementation. Remove these instructions._

- [IBM Natural Language Understanding](https://cloud.ibm.com/catalog/services/natural-language-understanding) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Assistant](https://cloud.ibm.com/catalog/services/watson-assistant) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Discovery](https://cloud.ibm.com/catalog/services/watson-discovery) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Speech to Text](https://cloud.ibm.com/catalog/services/speech-to-text) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Text to Speech](https://cloud.ibm.com/catalog/services/text-to-speech) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- List any additional [IBM AI services](https://cloud.ibm.com/catalog?category=ai#services) used or remove this line

### Other IBM technology used

INSTRUCTIONS: List any other IBM technology used in your solution and describe how each component was used. If you can provide links to/details on exactly where these were used in your code, that would help the judges review your submission.

### Solution architecture

Diagram and step-by-step description of the flow of our solution:

![Video transcription/translaftion app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.

## Presentation materials

_INSTRUCTIONS: The following deliverables should be officially posted to your My Team > Submissions section of the [Call for Code Global Challenge resources site](https://cfc-prod.skillsnetwork.site/), but you can also include them here for completeness. Replace the examples seen here with your own deliverable links._

### Solution demo video

[![Watch the video](https://raw.githubusercontent.com/Liquid-Prep/Liquid-Prep/main/images/readme/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)

### Project development roadmap

The project currently does the following things.

- Feature 1
- Feature 2
- Feature 3

In the future we plan to...

See below for our proposed schedule on next steps after Call for Code 2023 submission.

![Roadmap](./images/roadmap.jpg)

## Additional details

_INSTRUCTIONS: The following deliverables are suggested, but **optional**. Additional details like this can help the judges better review your solution. Remove any sections you are not using._

### How to run the project

INSTRUCTIONS: In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

