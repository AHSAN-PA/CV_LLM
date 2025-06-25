# CV_LLM
Created text promt based object detection
The main liberies used are openCV , hugging Face. Usin the libery owlv2 detecting the object in the image. And then using a LLM model to detech the object in a propmpt given "A car is present there", the LLM model convert into a list. Object  = ["car"]. This List is fetched into the Owlv2 model which show the percentage of presence of each object presenented in the prompt Sentence.
