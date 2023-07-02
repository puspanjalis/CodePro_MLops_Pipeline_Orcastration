# CodePro_MLops_Pipeline_Orcastration
> In this assignment, The focus is to work on reproducibility, automation and a few aspects of collaboration for CodePro is an EdTech startup.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- What is the background of your project?

CodePro is an EdTech startup that had a phenomenal seed A funding round. It used the money to increase its brand awareness. As the marketing spend increased, it got several leads from different sources. Although it had spent significant money on acquiring customers, it had to be profitable in the long run to sustain the business. 

- What is the business problem that your project is trying to solve?

The major cost that the company is incurring is the customer acquisition cost (CAC). Now, we will discuss what customer acquisition means.

At the initial stage, customer acquisition cost is required to be high in companies. But as their businesses grow, these companies start focussing on profitability. Many companies first offer their services for free or provide offers at the initial stages but later start charging customers for these services. For example, Google Pay used to provide many offers, and Reliance Jio in India offered free mobile data services for over a year. Once these brands were established and brand awareness was generated, these businesses started growing organically. At this point, they began charging customers. 

Businesses want to reduce their customer acquisition costs in the long run. There are many ways to do that. You will learn about these methods in the next segment.

The main objectives of lead scoring are as follows:

- Remove Junk by categorising leads on the basis of propensity to purchase
-Gain insights to streamline lead conversion and address improper targeting
-We have chosen L2AC (Leads to Application Completion) as our business metric, as choosing L2P (Leads to Payment) will aggressively drop the leads.
-A lead is generated when any person visits CodePro’s website and enters their contact details on the platform. A junk lead is generated when a person who --shares their contact details has no interest in the product/service.

- What is the dataset that is being used?

The dataset given is from Codepro's lead management system.

Inorder to classify any lead we will require 2 types of information about the lead. The 2 types are

 1.Source of origin of the lead:  In order to better predict the propensity of the lead to purchase the course, we need some information on the source of origin of the lead. The column from ‘city_mapped’ to ‘reffered_leads’ contain the information about the source of origin of the lead

 2.Interaction of the lead with the website/platform: In order to better predict the propensity of the lead to purchase the course, we need some information on what was the interaction of the lead with the platform. The column from ‘1_on_1_industry_mentorship’ to ‘whatsapp_chat_click’ store the information about the interaction the lead had with the platform.

## Technologies Used

- Jyupter Notebook
- Airflow
- MlFlow

## Contact
Created by [puspanjalis](https://github.com/puspanjalis) - feel free to contact me!
