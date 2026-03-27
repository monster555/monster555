<pre>
Initializing Dart VM...

Dart VM is ready to use.
To contact me, please send me a message to `<a href="mailto:danicoy@gmail.com">danicoy@gmail.com</a>`.
For more details, please visit <a href="https://portfoliolite.dctech.dev">https://portfoliolite.dctech.dev</a>.
MacBook-Pro:~ monster555$ cat ./main.dart
</pre>


```dart
void main() {
  const website = 'dctech.dev';
  const lite = 'portfoliolite.$website';
  
  final me = PersonalInfo(
    title: 'Senior Flutter Engineer',
    contactInfo: ContactInfo(
      email: Uri.parse('mailto:danicoy@gmail.com'),
      linkedIn: Uri.https('www.linkedin.com', 'in/daniel-coyula/'),
      github: Uri.https('github.com', 'monster555'),
      portfoliolite: Uri.https(lite),
      portfolio: Uri.https('portfolio.dctech.dev'),
      resume: Uri.https(lite, 'resume'),
    ),
    flutterInfo: FlutterInfo(
      experienceYears: '7+',
      projectsCount: 'Many!', // And counting...
      // Apps published on various stores
      apps: <Store>[
        AppStore(appsCount: 'many'), // iOS
        PlayStore(appsCount: 'many'), // Android
      ],
      architecturesAndTools: <String>[
        'BLoC',
        'Clean Architecture',
        'Firebase',
        'MongoDB',
      ],
    ),
    otherSkills: <String>[ // The most relevant
      'UI / UX',
      'NodeJS',
      'HTML / CSS'
    ],
    status: (
      learningCoolStuff: true,
      openToNewProjects: true,
    ),
    projects: <Project>[
      Project(
        'My Portfolio Lite',
        role: 'Senior Flutter Engineer',
        platforms: [.web],
        url: Uri.https(lite),
        techStack: ['Jaspr', 'Dart']
      ),
      Project(
        'Baseball Cuba',
        role: 'Senior Flutter Engineer',
        platforms: [.iOS, .android],
        url: Uri.https(lite, 'baseball-cuba'),
        metrics: 'Approaching 100K downloads',
      ),
      Project(
        'FlutterConf Latam - Official App',
        role: 'Lead Flutter Engineer',
        platforms: [.iOS, .android],
        isOpenSource: true,
        url: Uri.https('flutterconflatam.dev'),
      ),
      Project(
        'My Windows XP Portfolio',
        role: 'Senior Flutter Engineer',
        platforms: [.web],
        url: Uri.https('winxportfolio.dctech.dev'),
        metrics: '100+ countries',
      ),
      Project(
        'DateChatAI',
        role: 'Senior Flutter Engineer',
        platforms: [.iOS, .android],
        url: Uri.https('datechatai.com'),
      ),
      Project(
        'My Main Portfolio',
        role: 'Senior Flutter Engineer',
        platforms: [.web],
        url: Uri.https('portfolio.dctech.dev'),
        metrics: '185+ countries',
      ),
      Project(
        'ProAnimals',
        role: 'Senior Flutter Engineer',
        platforms: [.iOS, .android],
        url: Uri.https(lite, 'proanimals'),
      ),
      Project(
        'Cashews Finance',
        role: 'Senior Flutter Engineer',
        platforms: [.iOS, .android],
        url: Uri.https(lite, 'cashews-finance'),
      ),
      Project(
        'Self-Service kiosk for Citroën',
        role: 'Full Stack Software Engineer',
        platforms: [.android],
        url: Uri.https(lite, 'citroen'),
      ),
      Project(
        'PedidoFacil',
        role: 'Full Stack Software Engineer',
        platforms: [.iOS, .android],
        url: Uri.https(lite, 'pedidofacil'),
      ),
      Project(
        'EnvioFacil',
        role: 'Full Stack Software Engineer',
        platforms: [.iOS, .android],
        url: Uri.https(lite, 'enviofacil'),
      ),
    ],
  );
}
```
<pre>
MacBook-Pro:~ monster555$
</pre>
