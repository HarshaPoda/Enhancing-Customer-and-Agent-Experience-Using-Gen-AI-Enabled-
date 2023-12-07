# Enhancing-Customer-and-Agent-Experience-Using-Gen-AI-Enabled-

#Project Summary


1) Why did we choose this problem?


-> Contact centers encounter several critical challenges: long wait times leading to customer dissatisfaction and potential churn, limited service hours 
   restricting interaction, impersonal service impacting loyalty, high operational costs, scalability issues, inefficient data handling, and time-consuming 
   post-contact processing. 

2) How do we approach to provide a difference?

-> The integration of Gen AI addresses these issues by reducing wait times, enabling 24/7 service, personalizing interactions, cutting operational costs, 
   improving scalability, optimizing data analysis, and automating post-contact tasks.


<img width="637" alt="Screenshot 2023-12-06 at 6 20 52 PM" src="https://github.com/HarshaPoda/Enhancing-Customer-and-Agent-Experience-Using-Gen-AI-Enabled-/assets/55397511/b35abbba-3ef2-4ae7-9ea8-d02008068eb7">

   Moreover,Mckinsey has reported that Gen AI offers transformative benefits for contact centers in the following ways : 
     Enhanced productivity: Studies show a potential 14% increase in issue resolution per hour and a 9% reduction in handling time. 
     Improved service quality: Less-experienced agents benefit most, while overall productivity and quality rise. 
     Customer self-service: Up to 50% automation of customer inquiries is feasible through AI-powered chatbots. 
     Speedier responses: Real-time AI assistance reduces response times for sales representatives. Increased sales and coaching: AI-driven insights aid in 
     personalized sales strategies and agent coaching.

   Implementing Gen AI could potentially save contact centers 30 to 45% of current operational costs, focusing solely on direct productivity gains without 
   considering the potential boost in customer satisfaction from a more tailored experience.

<img width="490" alt="Screenshot 2023-12-06 at 6 19 59 PM" src="https://github.com/HarshaPoda/Enhancing-Customer-and-Agent-Experience-Using-Gen-AI-Enabled-/assets/55397511/3a506e96-0cdc-4bb2-a9a5-be09df676f73">


   Source:https://www.mckinsey.com/capabilities/mckinsey-digital/our-insights/the-economic-potential-of-generative-AI-the-next-productivity-frontier#business- 
   value

3) What is the difference that we have created through our solution?


<img width="605" alt="Screenshot 2023-12-06 at 6 15 51 PM" src="https://github.com/HarshaPoda/Enhancing-Customer-and-Agent-Experience-Using-Gen-AI-Enabled-/assets/55397511/ac02585b-3c62-4711-af6e-013e90a01ee0">

-> To enhance both customer’s and agent’s experience using GenAI ,we made the below solution.This solution utilizes AWS services such as 
   Connect,Bedrock,Kendra ,S3,Lambda and Lex.The Customer makes the call to the system, and the call is handled first by the lex chatbot and then, if 
   required ,by the human agent. The following two are the main integrations for our solution:

   Lex Chatbot Integration: Our Lex chatbot seamlessly integrates with AWS Bedrock housing the LLM model. Leveraging AWS Kendra, the chatbot scours policy 
   documents stored in S3, swiftly retrieving the most pertinent document matching the customer's query. Kendra's output fuels the LLM model, generating 
   personalized responses tailored to each customer query. 

   AWS Wisdom Integration: For customers preferring human interaction, our system seamlessly directs their call to a human agent via AWS Connect. 
   Additionally, by integrating AWS Connect with Wisdom, our agents receive real-time document recommendations based on the ongoing customer query. Wisdom 
   offers a ranked list of relevant documents, optimizing agent support and improving both customer experiences and agent productivity. 

   Our comprehensive integration of AI-driven models, AWS services, and real-time agent support mechanisms ensures a streamlined and personalized experience 
   for both customers and agents, setting a new standard in customer service delivery.     

