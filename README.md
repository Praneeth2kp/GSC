[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fishandeveloper%2FGoogle-DSC-Solution-Challenge&count_bg=%23EF466F&title_bg=%23EB2F5D&icon=googlekeep.svg&icon_color=%23E7E7E7&title=GDSC%20Solution%20Challenge%20Visits&edge_flat=true)](https://hits.seeyoufarm.com)
[![Flutter Version](https://img.shields.io/badge/flutter-%3E%3D%203.7.8-blue)](https://flutter.dev/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)


<img src="./designs/hero.png" width="100%"/>
  <h1 align="center"> GG </h1>
<p align="center">A <b>Google DSC Solution Challenge</b> submission</p>

<p align="center">The food donation app is a mobile application that offers a user-friendly platform for individuals and businesses to donate excess food to nearby charities and community groups. The app facilitates easy browsing of a list of available charities, allowing users to select the one they wish to support. Additionally, the app offers details on the impact of the user's donation, including the number of meals provided and the reduction in carbon emissions. Users can also receive notifications about new donation opportunities and keep up-to-date with their chosen charities. Overall, the food donation app is an effective and convenient means of reducing food waste and supporting the local community.</p>

### Video Submission

The link for our project demo can be found here👇👇👇

<a href="http://www.youtube.com/watch?v=dinzfBUDqi0">
<img src="https://img.youtube.com/vi/dinzfBUDqi0/maxresdefault.jpg" width="500px">                                                                                
</a>


### Project Info
The contents in this project follow the following structure, where all views are containerised into screens.

```
├───models
├───provider
├───resuable
├───screens
│   ├───alert
│   ├───community
│   ├───explorePage
│   ├───HomePage
│   ├───Login
│   ├───Profile
│
└───utils
```

Each individual screen in the above, follow this structure

```
screen
  ├──reusable_widgets
  └──filename.dart
```

#### Constants
This project uses 'Popins' as it's primary font. All the fonts have been pre-imported.

Moreover, here are a few constants which are used throughout the project, and have been added within a **CodeRedColors** class, use them accordingly.

```
base            : ED413E
primary         : FFFFFF
primaryAccent   : 9A9A9A
primary2        : ED413E
primary2Accent  : A4A4A4
inputFields     : F1F1F1
text            : 000000
textSecondary   : 9A9A9A
```

#### Designs

All the design/mockups for the app have been added in the `designs` directory. You can use those for reference.

### Description
 - Our solution mainly consists of a Flutter based mobile app. We wanted
   our solution to reach the masses, that's why we picked flutter as our
   framework of choice because of its cross-platform capabilities.
  
  - For the backend, we mostly relied on Firebase, as it was easier to
   integrate with the flutter app, without any hassle to manage & create
   instances of our server. 
   
  - For sign-up & authentication, we used Firebase auth. If you're a medical volunteer, we'll ask you to upload an image of your medical ID card and we're using firebase ml kit for verification.<br>
<img src="./designs/Auth.png" width="20%"><img src="./designs/Home - Screen.png" width="20%"><img src="./designs/Disease-Map.png" width="20%"><img src="./designs/Screenshot_20210401-103126.jpg" width="20%"><img src="./designs/Consult a doctor.png" width="20%">
   
  - For storing the different types of data including user data, posts
   for the forum, ambulances, insights for the heatmap, doctors,
   appointments etc. we chose Cloud Firestore because of its robust
   features and ability to query & filter out documents with ease.
   
  - For verifying the medical volunteer ID Card Image, we used Firebase
   ML Kit, specifically the text recognition service.
   
  - To enable image posting in forums, and to store the volunteer image
   we used firebase cloud storage.
   
  - For handling payments, we used Razorpay SDK, which allowed us to
   accept payments for doctor appointment booking using Google Pay.
   
  - Adding video-calling for doctors and users was a challenging part, we
   ended up using agora WebRTC SDK to enable that feature within the
   app.
   
  - For the symptom-based disease recognition system, we looked up a lot
   for a reliable resource and ended up using prepaid service from
   ApiMedic.
   
  - For the Google Assistant Action, we used actions SDK with Google
   Actions builder tool, along with that for hosting an instance for
   webhooks, we used GCP.

## Setup

  ##### Clone the repository
```bash
git clone https://github.com/ishandeveloper/Google-DSC-Solution-Challenge.git
```
  ##### Move to the desired folder
```bash
cd \Google-DSC-Solution-Challenge
```

  ##### To run the app, simply write
```bash
flutter run
```
## About
Solving real-life problems is not easy, but at the same time, it's not impossible. Keeping this in mind, a team of four student developers from Chitkara University, Punjab, worked throughout March to solve a concerning problem by leveraging tech.

Our app primarily deals with the health sector. When it comes to saving a life, every millisecond counts! One in 10 patients in India dies on the way to the hospital. And we're here to change to that. We're **Swaasthy**! 

##### Made with ♥ by 

<p align="left">
<a href="https://github.com/ishandeveloper"><img width="128px" src="https://avatars1.githubusercontent.com/u/54989142?s=460&u=4b787a0f50c1236b915d4766aa1a40c1b1d9f313&v=4"></a><a href="https://github.com/kushalbhanot"><img width="128px" src="https://avatars.githubusercontent.com/u/51001134?v=4"></a><a href="https://github.com/himanshusharma89"><img width="128px" src="https://avatars.githubusercontent.com/u/44980497?v=4"></a><a href="https://github.com/bhaveshgoyal182"><img width="128px" src="https://avatars.githubusercontent.com/u/60166991?v=4"></a>
</p>





For help getting started with Flutter, view the online documentation, which offers tutorials, samples, guidance on mobile development, and a full API reference.
