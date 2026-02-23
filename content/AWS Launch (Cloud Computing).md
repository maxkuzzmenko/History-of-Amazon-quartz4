In 2006 AWS released Amazon **Simple Storage Service (S3)**, which solved the problem of storing data while keeping it secure and easy to manage. 

A few months later, they released **Elastic Compute Cloud (EC2)**, which gave customers instant access to computer processing power in one click of a button. 

Each of the services are on a pay-as-you-go basis, meaning that you pay only for stuff you use.
They were the first Cloud Computing services AWS had to offer.

S3 and EC2 are still one of the most commonly used services even today, being able to help small as big businesses and everything in between with their low prices and, as I said, the pay-as-you-go basis. 

For instance, the current **S3 Standard** storage pricing in the **Frankfurt** region is:

| Storage Amount      | Pricing              |
| ------------------- | -------------------- |
| First 50 TB / Month | ```$0.0245 per GB``` |
| Next 450 TB / Month | ```$0.0235 per GB``` |
| Over 500 TB / Month | ``$0.0225 per GB``   |
50 GB of storage = 50 * \$0.0245 / Month = \$1.225 / Month

And some EC2 pricing also in the Frankfurt region:

| Instance name       | On-Demand hourly rate | vCPU | Memory    | Network performance |
| ------------------- | --------------------- | ---- | --------- | ------------------- |
| t4g.nano            | ``$0.0048``           | 2    | 0.5 GiB   | Up to 5 Gigabit     |
| t4g.micro           | ``$0.0096``           | 2    | 1 GiB     | Up to 5 Gigabit     |
| u7in-24tb.224xlarge | ``$326.6006``         | 896  | 24576 GiB | 200 Gigabit         |

month of 24/7 running a **t4g.nano** costs *(est.)*:<br>
\$0.0048 / Hour * 24 * 30 = \$3.456 / Month

That instance power is enough for the most of young startups
