# .github
**TrueNil: Genomic data discovery & protection tool**

**Overview**
TrueNil is an open-source sensitive data discovery and protection tool created to raise awareness among developers and security professionals regarding the security challenges posed by genomic data. 

**Security & Privacy Concerns related to Genomic Data**

In contrast to other types of sensitive data like credit card or social security numbers, insecure handling of genomic data poses unique implications:

**A. Privacy Concerns**

Small pieces of genomic data combined with other information can lead to inference attacks.

**B.National Security Concerns**

1. Genomic data could be exploited for population surveillance, oppression, or extortion against citizens, military, and intelligence personnel.
2. Inadequate integrity controls on genomic data could allow manipulation to produce toxic products or infectious agents, resulting in loss of life and economic damage.
3. Large genomic databases could potentially be used in bioweapon development due to their extensive genetic information, which could be exploited to identify vulnerabilities or targets.

**C. Unintended Consequences from Sample Bias**

AI and statistics use large genomic datasets to identify diseases, assess risks, determine treatments, and predict patient outcomes. However, minority groups are often underrepresented in this data. This exacerbates biases, particularly in AI, potentially leading to unfair results in analyses and predictions.

(Reference: NIST IR 8432 “Cybersecurity of Genomic Data”)

**Motivation**

Genomic data plays a crucial role in modern healthcare, holding immense potential for personalized medicine and targeted therapies. But harnessing this power requires robust IT infrastructure, secure data handling, and developer-friendly tools. There are several types of genomics companies that specialize in various areas of genomics research and application. Here are some of the most common types:

1. Genomic sequencing companies specialize in providing DNA sequencing services to researchers, healthcare providers, and individuals. These are specialized data pipelines for processing the massive amounts of raw sequence data generated by machines. Developers ensure efficient data flow, integration with analysis tools, and scalability for future growth. Security is paramount here, protecting sensitive patient information

2. Genomic data analytics companies: These companies develop software and analytics tools to help researchers and clinicians interpret genomic data. These platforms provide the computational muscle for analyzing genomic data. Developers build and maintain these platforms, focusing on data visualization, secure access controls, and integration with external tools and databases.

3. Genomic medicine companies use genomic data to develop personalized therapies and diagnostics for patients. They rely on a collaborative effort between IT, development, and security professionals to securely manage, analyze, and leverage the power of genetic data for personalized medicine

4. Direct-to-consumer genomics companies  provide genetic testing services directly to consumers, allowing individuals to learn about their genetic risks for certain diseases and ancestry. They prioritize responsible use of genetic information through secure data handling, user-friendly interfaces, and clear communication about data usage to build trust with their customers.

5. Synthetic biology companies: These companies engineer biological systems using genetic engineering techniques to create new drugs, materials, and organisms. Synthetic biology raises concerns about potential misuse. Security teams implement measures to prevent unauthorized access to sensitive genetic data that could be used for harmful purposes.

6. Genomic Data Storage and Analysis Platforms: With the growing volume of genomic data, there are companies that specialize in providing secure storage, management, and analysis platforms specifically designed for genomic data. These platforms enable researchers and clinicians to store, access, and analyze large-scale genomics datasets efficiently.

7. Gene and cell therapy companies analyze genetic data to understand the root cause (such as missing or mutated gene) of diseases they are targeting. This information is used to create modified genes to deliver to a patient's cells or identify the best way to edit a patient's genes. Protecting such platforms requires a multi-layered approach. By implementing robust security measures, platforms can build trust with users and ensure the responsible use of this sensitive information for scientific progress and personalized medicine.

8. mRNA-based therapeutics companies identify targets, design therapies, understand disease mechanisms, personalize treatments, and optimize delivery systems, ultimately leading to the creation of more effective and innovative treatments for a wide range of diseases. They invest heavily in researching and developing mRNA therapies. Theft of trade secrets related to target identification, mRNA design, or delivery systems could give competitors an unfair advantage. Robust cybersecurity measures and employee training on data security are crucial.

**TrueNil Key Features** 

* TrueNil is a multi tenant SaaS application hosted in AWS built to detect sensitive data stored in S3 buckets and DynamoDB:
* User registration
* User authentication using google SSO
* Agent health check 
* Truenil discovers and  detects sensitive data like genomic data, PII data, PCI data and certain type of PHI data
* TrueNil allows access to executive risk dashboard using Google’s Single Sign On (SSO)
* TrueNil detects human and non-human access to the sensitive data 
* TrueNil detects the encryption at rest status of the sensitive data
* If AWS cloud trail is enabled then, TrueNil tracks user’s action performed on sensitive data
* Granular role-based access control to ensure that only authorized users can access data 
  Superadmin
  Researcher
  Operator

**Intended Audience**

* Anyone who would like to discover and protect genomic data
* IT, developers, security engineers working with applications and systems processing genomic data
* Data privacy officers or chief security officers who would like to see one stop view of genomic data and their security posture
  
