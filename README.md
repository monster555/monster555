<pre>
Initializing Dart VM...

Dart VM is ready to use.
To contact me, please send me a message to `<a href="mailto:danicoy@gmail.com">danicoy@gmail.com</a>`.
For more details, please visit <a href="https://dctech.dev">https://dctech.dev</a>.
MacBook-Pro:~ monster555$ cat ./main.dart
</pre>


```dart
void main() {
  final portfolioUrl = 'dctech.dev';
  final myEmail = 'danicoy@gmail.com';
  
  final me = PersonalInfo(
    title: 'Senior Flutter Engineer',
    contacInfo: ContactInfo(
      email: Uri.parse('mailto:$myEmail'),
      linkedIn: Uri.https('www.linkedin.com', 'in/daniel-coyula/'),
      website: Uri.https(portfolioUrl),
      resume: Uri.https(portfolioUrl, 'downloads/CV-Daniel_Coyula.pdf'),
    ),
    flutterInfo: FlutterInfo(
      experienceYears: 5,
      apps: [
        IOS(
          hasPublishedApps: true,
          appsCount: 3,
        ),
        Android(
          hasPublishedApps: true,
          appsCount: 4,
        ),
      ],
      useBLoC: true,
      useCleanArchitecture: true,
      useFirebase: true,
      useParseServer: true,
      useFlutterWeb: true,
    ),
    otherSkills: [
      'UI / UX',
      'MongoDB',
      'JavaScript',
      'NodeJS',
      'HTML / CSS',
      'TypeScript',
      'Ionic Framework',
      'Express',
      'React',
      'NextJS'
    ],
    projects: [
      Project(
        'Cashews Finance',
        role: 'Senior Flutter Engineer',
        platforms: Platforms(androidVersion: true, iosVersion: true),
        url: Uri.https(portfolioUrl, 'cashews-finance'),
      ),
      Project(
        'KOBA Insurance',
        role: 'Full Stack Senior Developer',
        platforms: Platforms(webVersion: true),
        url: Uri.https(portfolioUrl, 'koba'),
      ),
      Project(
        'Self-Service kiosk for Citroën',
        role: 'Full Stack Software Engineer',
        platforms: Platforms(androidVersion: true),
        url: Uri.https(portfolioUrl, 'citroen'),
      ),
      Project(
        'PedidoFacil',
        role: 'Full Stack Software Engineer',
        platforms: Platforms(androidVersion: true, iosVersion: true),
        url: Uri.https(portfolioUrl, 'pedidofacil'),
      ),
      Project(
        'EnvioFacil',
        role: 'Full Stack Software Engineer',
        platforms: Platforms(androidVersion: true, iosVersion: true),
        url: Uri.https(portfolioUrl, 'enviofacil'),
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
  <img src="https://github.com/monster555/monster555/blob/main/parse-server-logo.svg" title="Parse Server" alt="Parse Server" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mongodb/mongodb-original.svg" title="MongoDB" **alt="MongoDB" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/npm/npm-original-wordmark.svg" title="NPM" alt="NPM" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/express/express-original.svg" title="Express" alt="Express" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-original.svg" title="TypeScript" alt="TypeScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/tensorflow/tensorflow-original.svg" title="TensorFlow" alt="TensorFlow" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nextjs/nextjs-original.svg" title="NextJS" alt="NextJS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/ionic/ionic-original.svg" title="Ionic" alt="Ionic" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/androidstudio/androidstudio-original.svg" title="Android Studio" alt="Android Studio" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/xcode/xcode-original.svg" title="Xcode" alt="Xcode" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/slack/slack-original.svg" title="Slack" alt="Slack" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/jira/jira-original.svg" title="Jira" alt="Jira" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
</div>
