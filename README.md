<pre>
Initializing Dart VM...

Dart VM is ready to use.
To contact me, please send me a message to `<a href="mailto:danicoy@gmail.com">danicoy@gmail.com</a>`.
For more details, please visit <a href="https://portfolio.dctech.dev">https://portfolio.dctech.dev</a>.
MacBook-Pro:~ monster555$ cat ./main.dart
</pre>


```dart
void main() {
  const websiteUrl = 'dctech.dev';
  
  final me = PersonalInfo(
    title: 'Senior Flutter Engineer',
    contactInfo: ContactInfo(
      email: Uri.parse('mailto:danicoy@gmail.com'),
      linkedIn: Uri.https('www.linkedin.com', 'in/daniel-coyula/'),
      github: Uri.https('github.com', 'monster555'),
      portfolio: Uri.https('portfolio.dctech.dev'),
      winxportfolio: Uri.https('winxportfolio.dctech.dev'),
      facefolio: Uri.https('facefolio.dctech.dev'),
      website: Uri.https(websiteUrl),
      resume: Uri.https(websiteUrl, 'downloads/viewDanielCoyulaCV().pdf'),
    ),
    flutterInfo: FlutterInfo(
      experienceYears: '6+',
      projectsCount: 'Many!', // And counting... :)
      // Apps published on various stores
      apps: <Store>[
        // iOS apps in the App Store
        AppStore(appsCount: 'many'),
        // Android apps in the Play Store
        PlayStore(appsCount: 'many'),
      ],
      architecturesAndTools: <String>[
        'BLoC',
        'Clean Architecture',
        'Firebase',
        'MongoDB',
        'Parse Server',
        'Flutter Web',
      ],
    ),
    otherSkills: <String>[ // The most relevant
      'UI / UX',
      'JavaScript',
      'NodeJS',
      'HTML / CSS',
      'Express'
    ],
    projects: <Project>[
      Project(
        'My Windows XP Portfolio',
        role: 'Senior Flutter Engineer',
        platforms: ['Web'],
        url: Uri.https('winxportfolio.dctech.dev'),
      ),
      Project(
        'DateChatAI',
        role: 'Senior Flutter Engineer',
        platforms: ['iOS', 'Android'],
        url: Uri.https('datechatai.com'),
      ),
      Project(
        'My FaceFolio',
        role: 'Senior Flutter Engineer',
        platforms: ['Web'],
        url: Uri.https('facefolio.dctech.dev'),
      ),
      Project(
        'Baseball Cuba',
        role: 'Senior Flutter Engineer',
        platforms: ['iOS', 'Android'],
      ),
      Project(
        'My Flutter Web Portfolio',
        role: 'Senior Flutter Engineer',
        platforms: ['Web'],
        url: Uri.https('portfolio.dctech.dev'),
      ),
      Project(
        'ProAnimals',
        role: 'Senior Flutter Engineer',
        platforms: ['iOS', 'Android'],
      ),
      Project(
        'Cashews Finance',
        role: 'Senior Flutter Engineer',
        platforms: ['iOS', 'Android'],
        url: Uri.https(websiteUrl, 'cashews-finance'),
      ),
      Project(
        'Self-Service kiosk for Citroën',
        role: 'Full Stack Software Engineer',
        platforms: ['Android'],
        url: Uri.https(websiteUrl, 'citroen'),
      ),
      Project(
        'PedidoFacil',
        role: 'Full Stack Software Engineer',
        platforms: ['iOS', 'Android'],
        url: Uri.https(websiteUrl, 'pedidofacil'),
      ),
      Project(
        'EnvioFacil',
        role: 'Full Stack Software Engineer',
        platforms: ['iOS', 'Android'],
        url: Uri.https(websiteUrl, 'enviofacil'),
      ),
    ],
  )..setStatus(
    learningCoolStuff: true,
    openToNewProjects: true,
  );
}
```
<pre>
MacBook-Pro:~ monster555$
</pre>
  
## Apps on Stores

<a href="https://apps.apple.com/us/developer/daniel-coyula/id1396312930" target="_blank">iOS apps on App Store</a><br>
<a href="https://play.google.com/store/apps/developer?id=DC+Tech" target="_blank">Android apps on Play Store</a>

## Some stuff I've used

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/flutter/flutter-original.svg" title="Flutter" alt="Flutter" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/dart/dart-original.svg" title="Dart" alt="Dart" width="40" height="40"/>&nbsp;
  <img src="https://github.com/monster555/monster555/blob/main/bloc-logo.svg" title="BLoC" alt="BLoC" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/firebase/firebase-plain.svg" title="Firebase" alt="Firebase" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mongodb/mongodb-original.svg" title="MongoDB" alt="MongoDB" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/npm/npm-original-wordmark.svg" title="NPM" alt="NPM" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/express/express-original.svg" title="Express" alt="Express" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/tensorflow/tensorflow-original.svg" title="TensorFlow" alt="TensorFlow" width="40" height="40"/>
</div>
