# Why do we need to moniter?

Monitoring is essential for ensuring the health, performance, and availability of your applications and infrastructure. Some reasons why we should use monitoring are:

- Early detection of issues: Monitoring allows you to detect and identify issues before they become critical. This helps you to proactively address problems, minimize downtime, and prevent service disruptions.

- Improved system performance: Monitoring helps you to identify bottlenecks, optimize resource utilization, and improve system performance. By analyzing performance metrics, you can make data-driven decisions to optimize your infrastructure and application performance.

- Increased reliability and availability: Monitoring helps you to ensure that your applications and services are always available to your users. By monitoring your system, you can identify and resolve issues quickly, minimize downtime, and improve system reliability.

- Better user experience: Monitoring helps you to understand how your application is performing from the user's perspective. By monitoring user experience metrics, such as response time and availability, you can ensure that your users have a positive experience when using your application.

- Cost optimization: Monitoring helps you to optimize your infrastructure and application costs by identifying areas of inefficiency, overutilization, or underutilization. By optimizing resource utilization, you can reduce costs and improve your return on investment.

Monitoring is critical for ensuring the health, performance, and availability of your applications and infrastructure. It allows you to identify and resolve issues quickly, optimize performance, and improve the user experience.

#
# What are the 4 golden rules of monitering?

The four golden rules of monitoring are:

- Know your baseline: Establish a baseline for your application's performance and behavior under normal conditions. This baseline provides a reference point for identifying and diagnosing anomalies and deviations from expected behavior.

- Monitor proactively: Monitor your application and infrastructure proactively to identify issues before they become critical. This helps to minimize downtime, prevent service disruptions, and improve overall system reliability.

- Use meaningful metrics: Use metrics that are relevant and meaningful to your application's performance and business objectives. Collect data on key performance indicators (KPIs) such as response time, throughput, error rates, and resource utilization.

- Automate wherever possible: Use automation to streamline monitoring and alerting processes. Automate data collection, analysis, and reporting to reduce the risk of human error and ensure timely notifications of critical events. This also helps to minimize manual intervention and frees up resources for other important tasks.

#
# What is Alert Management?

#
# Monitering diagram:

<img width="591" alt="Monitering-diagram" src="https://user-images.githubusercontent.com/129315605/235124691-ce5032ac-a880-403f-8bc8-c4b942b33123.png">
<img width="454" alt="Cloudwatch-monitering" src="https://user-images.githubusercontent.com/129315605/235125004-a89341a6-9925-40e6-9ea2-44db5a949b64.png">


#
# Setting up a Cloud Watch alarm that sends a notification when CPU usage is greater than 50%

1. Head to the Simple Notification Service dashboard
2. Select subsciptions and create a subscription (if you have not yet created one)
3. Select Topics and Create a topic
4. Choose the Standard type, name the topic and then create it
5. Head back to the EC2 dashboard and select your instance
6. Select Monitoring/Monitor and troubleshoot/Manage CloudWatch alarms
7. Create alarm and Select your notification that you created
8. Set the alarm threshold (in this case, >= 50% cpu utilisation), name the alarm and select Create
- Your Alarm is now set up on the instance
- You can test the alarm by running an infinite while loop on the instance


