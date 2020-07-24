## Welcome to Wapelo's Page

### ABSTRACT
COVID 19 has hit all countries worldwide it has become a global pandemic .It is therefore very important for country government  to take precautions in ensuring that the virus is controlled in their respective countries. In trying to do this there are some factors that have to be looked at such as how the virus is spread and how it can be avoided. It is very necessary that contact tracing apps have to be developed in order to help keep track of who one has been in contact with. Therefore the government of Botswana and other countries have developed applications which try in contact tracing. It is with no doubt that the world is evolving we are looking into the 4th industrial revolution whereby most things will be computerized. There is a need to use mobile phones applications for contact tracing as 70% of Batswana have smartphones. Therefore there is no need for using the old pen and paper method for registration. The applications will be used for better database updates.



### 2.0 INTRODUCTION
There have been several diseases emerging in new geographical locations for the past decade. These diseases include HIV/AIDS which is one disease which hit hard in African countries including Botswana. We have other disease such as malaria, EBOLA, Spanish flu, Swine flu and Zika. Recently a new type of viral infection has emerged in the city of Wuhan in China known as coronavirus (COVID-19) in late 2019. This virus has posed as a global health threat with its ongoing pandemic in many countries. Coronaviruses are a large family of viruses that cause respiratory infections. These can range from the common cold to more serious diseases. This disease has become a world pandemic as all the countries are affected by it. Since it is a new disease how it is spread is still not know, but the basics is that people should be hygienic and sanitize and disinfect all the time as similar viruses are spread in cough droplets. It is also advised that people should observe social distancing in order to limit the transmission of the virus. People are advised to fill in registers of the places they have visited tis is to help trace them if at all there was an infected person in the place where they visited. The old method of pen and paper has been used for registration, but it can also lead to the spread of the virus as people will keep exchanging the same pen and paper as they register. Contact tracing is a key approach for controlling the COVID–19 pandemic. Traditional tracing methods might however miss a number of contacts between infected and susceptible persons. Digital contact tracing apps have been developed to assist health departments in notifying individuals of recent exposures to SARS-CoV-2. These apps are used in several countries throughout the world. In Botswana about 70% of the citizens have smartphones therefore it is very necessary to digitalize the contact tracing process. Countries are moving onto the 4th industrial revolution where everything is computerized. The BSafe application app has been developed to help in contact tracing in Botswana, however it has some downfalls which this document will be pointing out and finding ways of mitigating the downfalls of the application.

### 2.1 OBJECTIVES
•	To find out the downfalls of already existing contact tracing applications
•	To have an overview of the already existing contact tracing applications
•	To find out ways to mitigate the downfalls of the already existing application
•	To develop a prototype of a contact tracing application

### 2.2 SCOPE
The contact tracing mobile application which functions is to notify users when they have been in recent proximity with another user who has confirmed symptoms of COVID19 (whether via official or self-diagnosis). It uses ‘proximity data’ which consists of identifiers broadcast by pairs of devices that have been close to each other (possibly including how close they were, and for how long). One typical approach involves generating identifiers and the matching process taking place on-device, while another involves these processes being driven by the backend infrastructure. In popular parlance these have become known as decentralized and centralized approaches.


### 3.0 LITERATURE REVIEW & TECHNOLOGY ASSESSMENT

### 3.1 LITERATURE REVIEW

GERMANY

“Datenspende-App”: There are several concerns indicated by Chaos Computer Club, a cyber-security NGO, in particular: 
•	RKI can directly retrieve the fitness data from the provider of the fitness tracker or Google Fit and only then the data will be pseudonymized (except Apple Health). As the RKI also stores access data to the fitness tracker, it can be used to access complete history and names of the users. 
•	Easy reversal of the pseudonymisation and the insecure handling of the confidential pseudonym as the app does not use a standard browser but an embedded web view which is insecure due to man-in-the-middle attacks. 
•	The RKI server exposes additional functionality such as a management and admin interface as well as a SOAP API via the Internet. This increases its vulnerability.
“Corona-Warn-App”: - There are no major privacy concerns as the Corona-Warn-App has been designed with a special focus on privacy from the beginning. The German Data Protection Authorities generally support the Corona-Warn-App and only expressed minor concerns, but less on the Corona-Warn-App itself but rather on the way it may be used: 
•	As Apple and Google, as providers of the operating systems, have access to all data that runs over their interfaces, there are some concerns regarding the Intension of Apple and Google. 
•	The voluntary aspect of the Corona-Warn-App could be undermined through social or economic pressure which could be specifically enforced by employers. It is proposed that a special accompanying law (which has not been passed, drafts of opposition parties available) is required to address these issues. (Ritzer, 2020)
CANADA
The Government of the Province of Alberta has introduced a mobile contact tracing app, “ABTraceTogether” (Alberta App), which utilizes Bluetooth with the aim of letting users know if they have been exposed to COVID-19 or exposed others. Alberta’s “ABTraceTogether” app was developed using the same code that formed basis of Singapore’s “Trace Together” App. Currently the government of the Province of Alberta is the only Canadian government to introduce a COVID-19 contact tracing app. 
The Federal Government of Canada has begun testing a mobile-based contact tracing app to be used nationwide. The app, which also will utilize Bluetooth technology, will compile confirmed positive COVID-19 cases nationwide and will notify Canadians when they have been in close proximity to others who have received a positive diagnosis of COVID-19. The Federal Government of Canada has signaled that the voluntary, free app will be available for download beginning in early July. The Federal Privacy Commissioner of Canada (Canada’s Federal Privacy Regulator) has not yet issued a set of specific recommendations regarding the proposed Canada-wide app.
The App is viewed to be minimally intrusive from a privacy perspective (especially in light of Alberta Privacy Commissioner’s positive comments) as it is voluntary and collects very little information, which is only used for the limited purpose of contacting users in the event of a positive test. Major privacy concerns center around employers potentially requiring employees to download the app as a condition of being permitted to return to the workplace. Currently a major issue is that there is insufficient uptake within the population for the app to be effective and technological issues in that the app is always required to be open and on to work properly and transmission can be interrupted while other phone applications are being used (i.e. email). (Tsekouras, 2020)
BOTSWANA
BSafe is the Official Digital Contact Tracking Application by Govt. of Botswana. This app records entry and exit of persons who have valid permits around the country so that contact tracing is made easier when a user is diagnosed with the disease.
Issues of privacy are embedded in almost all platforms where users have to include their information online. With confirmation of the Indonesian database of COVID-19 contact tracing app being hacked, it is pivotal to understand and fully grasp issues of privacy when it comes to any electronic application, and in this case our very own Bsafe app.
The COVID-19 Task Force has just said the application complies with the legal framework that protects a user’s right to privacy. Section 28 of the Data Protection Act states that the data controller or processor shall, where personal data is obtained directly from the data subject, provide the following information to the data subject, except where the data subject already has the information.
Everyone involved in contact tracing must adhere to the ethical principles of handling personal information to ensure responsible data management and respect for privacy throughout the process. But how data will be handled, stored and used needs to be communicated to those concerned in a clear and transparent manner. This is important for buy-in and engagement, as well as to avoid misperceptions that could jeopardize the effectiveness of a contact tracing programme.
However, these guidelines seem to have not been applied by the BSafe app, leaving questions of uncertainty on the application’s intention beyond contact tracing. The COVID-19 Task Force has not let the public know what security safeguards there are. In this way their approach was different from the world over where contact tracing apps were assessed by anyone who cared to before they launched and the technologies used on them are open to the public.

SOUTH AFRICA
The South African government has partnered with the University of Cape Town to develop a smartphone app to assist government with tracking people who may be unaware that they have COVID-19 and to track people who have come into contact with others who are COVID-19 positive. The App is called Covi-ID. The South African Government acknowledged that it is critical that the Government works collaboratively with South African technology companies and individuals to leverage technology capabilities in the fight against COVID-19 and its effects. We are aware that the Government has approached technology companies to identify suitable projects that may assist the Government with its response to the crisis, in particular, its plan to develop a national COVID-19 Tracing Database. The database seeks to track people who are known or suspected to have come into contact with persons known or suspected to have COVID-19. On 2 May 2020, the Department of Health also launched a WhatsApp based symptom reporting process. The details of the back end and privacy controls are unknown at this stage.
Given that South African privacy laws are not yet in force, there is a concern that personal information may not be properly protected during the pandemic and may be used for further processing not anticipated on collection of the data. On the WhatsApp symptom tracker it is unclear who is processing the information submitted and where else it may be disclosed. There are no terms and conditions available regarding the use of this functionality. Even though South African privacy laws are not in place, there is a constitutional right of privacy; however this may be infringed where there are larger public interest considerations that outweigh the impact on privacy. The Covi-ID App has a GDPR-based privacy policy and also voluntarily submits to the South African data privacy laws not yet in place.  (Ritzer, 2020)
### 3.2 TECHNOLOGY ASSESMENT

### LOCATION	NAME	TECHNOLOGY

ALGERIA	ALGERIA’S APP	TBD

AUSTRALIA	COVIDSafe	BLUETOOTH

AUSTRIA	STOPP CORONA	BLUETOOTH, GOOGLE/APPLE

BAHRAIN	BeAware	Bluetooth, location

BELGIUM 	BELGIUM’S APP	BLUETOOTH, GOOGLE/APPLE

BOTSWANA	BSAFE APP	QR CODES

BULGARIA	ViruSafe	LOCATION

CANADA	COVID alert*	BLUETOOTH, GOOGLE/APPLE

CHINA
	Chinese health code system
	Location, data mining
CYPRUS
	CoyTrscer	LOCATION, GPS
CZECH	eRouska	BLUETOOTH

DENMARK	Smitterstop	BLUETOOTH, GOOGLE/APPLE

ESTONIA	ESTONIA’S APP	BLUETOOTH, DP-3T, GOOGLE/APPLE

FIJI	CareFiji*	BLUETOOTH, DP-3T

FINLAND	Ketju*	BLUETOOTH, DP-3T

FRANCE	StopCovid*	BLUETOOTH

GERMANY	Corona-Warn-App	BLUETOOTH, GOOGLE/APPLE

GHANA	GHCOVID-19 Tracker	LOCATION

GIBRALTAR	Beat Covid Gibraltar*	TBD

HUNGRAY	VirusRadar	BLUETOOTH

ICELAND 	Ranking C-19	LOCATION

INDIA	Aarogya Setu	BLUETOOTH, LOCATION

INDONESIA	PeduliLindungi	TBD

IRAN	Mask ir	LOCATION

IRELAND	HSE Covid-19 APP*	BLUETOOTH, GOOGLE/APPLE

ISRAEL	HaMagen	LOCATION

ITALY
	Immuni	BLUETOOTH, GOOGLE/APPLE

JAPAN	COCOA	GOOGLE/APPLE

KUWAIT	Shlonilk	LOCATION

MALAYSIA	MyTrace	BLUETOOTH, GOOGLE/APPLE

MEXICO	CovidRadar	BLUETOOTH

NEW ZEALAND	NZ COVID Tracer	BLUETOOTH, QR codes

NORTH MACEDONIA	StopKorona	BLUEETOOTH

NORTHERN IRELAND	Northern Ireland’s app	BLUETOOTH, GOOGLE/APPLE

NORWAY	Smittestopp	BLUETOOTH, LOCATION

PHILIPPINES	StaySafe	BLUETOOTH

POLAND	ProteGO	BLUETOOTH

QATAR	Ehteraz	BLUETOOTH, LOCATION
SAUDI ARABIA	Tabaud	TBD

SINGAPORE	Trace Together	BLUETOOTH, BlueTrace

SWITZERLAND	Swiss Contact Tracing App
	BLUETOOTH
SOUTH AFRICA	Covi-ID	BLUETOOTH, LOCATION

THAILAND	MorChana	QR codes

TUNISIA	E7mi	BLUETOOTH

TURKEY
	HayatEve Sigar	BLUETOOTH, LOCATION

UAE
	TraceCovid	BLUETOOTH
UK 
	NHS COVID-19 App	BLUETOOTH, GOOGLE/APPLE

Vietnam	BlueZone	TBD


### 4.0 CHALLENGE DEFINITION


### ID
Challenge 001
### CATEGORY
Health/e-health
### TITLE
BSafe application
### BACKGROUND
BSafe is the Official Digital Contact Tracking Application by Govt. of Botswana. This app records entry and exit of persons who have valid permits around the country so that contact tracing is made easier when a user is diagnosed with the disease.

### DESCRIPTION
The Bsafe application has been designed for Batswana to be able to keep track of who they were in contact with. it uses the QR code technology to be able to allow people to register their presence in a premise, by scanning the code and it will save it in the database. The user can also be able to view the history/ summary of the places they have been to. This app however has some downfalls which I will like to point out and be able to come up with a better interface which will show where the app needs to be developed

### LIST OF SKILLS REQUIRED/AQUIRED
•	Creativity
•	Problem solving
•	Analytic skills
•	Programming languages skills
•	Communication skills
### LIST OF HARDWARE/SOFTWARE NEEDS
•	Android studio
•	Flutter
•	Pc
•	Android phone
STAKEHOLDER

PUBLIC

DOWNFALL FOR THE BSAFE APP
•	There is no confirm password feature 
•	There is no forgot password feature which makes it difficult to retrieve the account
•	The interfaces need to be improved to make them user friendly
•	Registering an organization that have different offices and address in more than location
•	The history of events is sometimes not shown
•	It does not show the people one has contacted in a smaller scale

### 6.0 IMPLEMENTATION DIRECTIONS

### BLUETOOTH IMPLEMENTATION

 
The database here is decentralized so that information about people is kept anonymous .If two people using the application get into contact with each other information of both devices will be captured and put in databases. If the person you have been in contact with was found to have tested positive for coronavirus then the other user who was in contact with the infected person is notified and sent a message that he/she has to visit the nearest clinic to test for the virus.



If the internet is low/down the user can just manually type in their details and send to register The details of the user are then stored in the database and if needed will be used to keep track of the location the user. 

### CONCLUSION
In conclusion It is very important to look at already existing apps and look for their downfalls in order to improve them and make them work better. Covid -19 has made technologies such as contact tracing to be developed. It has destroyed a lot of things, but it was an eye open to let people realized the importance of always being up to date with technological devices.




### Done by Wapelo 
