# Politique de confidentialité de Subwhere Paris

*English version below.*

Dernière mise à jour : 15 octobre 2026

La présente politique de confidentialité décrit la manière dont Subwhere Paris (« Subwhere » sur votre écran d'accueil ; « l'Application », « nous ») traite les informations lorsque vous utilisez l'Application et ses widgets sur iOS et Android.

Subwhere Paris est publiée par AppLand (Stefan Almqvist), établie en Suède.

Contact : <applandapps@gmail.com>

## En bref

L'Application ne collecte aucune donnée personnelle. Il n'y a ni compte, ni outil de mesure d'audience, ni publicité, ni pistage. Votre position et l'image de votre caméra ne nous sont jamais envoyées. Pour afficher les trains en direct, l'Application télécharge les données du Métro par l'intermédiaire d'un petit service que nous exploitons. Ces requêtes ne contiennent ni compte, ni identifiant, ni coordonnées de localisation, et nous n'en gardons aucune trace. La vue en réalité augmentée utilise les services de réalité augmentée d'Apple ou de Google, qui traitent les données comme décrit aux rubriques « Services Apple » et « Services Google ».

## Ce que l'Application utilise sur votre appareil

**Flux de la caméra.** Utilisé par le framework de réalité augmentée de votre appareil (ARKit d'Apple sur iPhone et iPad, Services Google Play pour la RA sur Android) pour afficher la vue en réalité augmentée et reconnaître les bâtiments qui vous entourent, afin que les trains s'alignent sur la rue. L'Application n'enregistre, ne sauvegarde et ne nous envoie jamais l'image de la caméra. Sur Android, Google traite les données de la caméra pour faire fonctionner la session de RA (voir « Services Google »).

**Position.** Utilisée pour placer les trains par rapport à l'endroit où vous vous trouvez, pour trouver la station la plus proche et vous en indiquer la direction, et, sur iPhone et iPad, pour choisir la station qu'affiche le widget. L'Application utilise votre position sur votre appareil. Elle ne nous est jamais envoyée, n'est jamais conservée sous forme d'historique de positions, et n'est jamais partagée ni vendue. Sur Android, Google traite les données de localisation pour faire fonctionner la session de RA (voir « Services Google »).

**Mouvements de l'appareil et cap de la boussole.** Utilisés pour la vue en RA et la boussole vers la station. Traités uniquement sur votre appareil.

**Données conservées sur votre appareil.** Pour que le widget fonctionne sans ouvrir l'Application, celle-ci conserve les noms des stations du Métro et de leurs quais, les derniers départs de la station la plus proche et des stations de vos widgets, ainsi que les horaires du jour des stations récemment les plus proches ou choisies. Elle mémorise aussi votre choix de langue et si vous avez vu l'introduction. Rien de tout cela ne nous est envoyé, et tout est supprimé lorsque vous supprimez l'Application.

Nous n'utilisons aucun outil de mesure d'audience, SDK de pistage, publicité, service de rapports de plantage ni aucune autre collecte de données par des tiers. L'Application n'utilise pas d'identifiant publicitaire et ne vous suit pas à travers les applications ou sites web d'autres sociétés.

## Widgets

Subwhere Paris propose des widgets facultatifs qui affichent les prochains départs.

Sur iPhone et iPad, les widgets de l'écran d'accueil et de l'écran verrouillé affichent soit une station que vous choisissez, soit, par défaut, la station la plus proche de vous. Pour trouver la station la plus proche, un widget lit la position de votre appareil sur votre appareil, y compris lorsque l'Application est fermée. Comme dans l'Application, votre position sert uniquement, sur votre appareil, à déterminer la station la plus proche. Elle n'est jamais conservée sous forme d'historique, ne nous est jamais envoyée, et n'est jamais partagée ni vendue.

Sur Android, le widget de l'écran d'accueil affiche une station que vous choisissez. Il n'utilise pas votre position.

## Données des trains en direct

Les départs, les prévisions de passage des trains, les horaires et les informations trafic proviennent des données ouvertes d'Île-de-France Mobilités, publiées sur sa plateforme PRIM. L'Application ne contacte pas elle-même Île-de-France Mobilités. Elle interroge un petit service qu'AppLand exploite sur Cloudflare, qui récupère les données auprès de PRIM, les stocke et les transmet. Cela permet de garder notre clé d'accès PRIM hors de l'Application et de limiter la charge sur PRIM. Subwhere Paris n'est ni affiliée à Île-de-France Mobilités ou à la RATP, ni approuvée par elles.

Ces requêtes ne contiennent ni compte, ni identifiant d'appareil, ni coordonnées de localisation. La plupart demandent les prévisions pour l'ensemble du réseau ou les informations trafic de toutes les lignes, qui sont les mêmes pour tout le monde. Lorsque l'Application ou un widget a besoin des départs ou des horaires d'une seule station, la requête indique les quais de cette station et rien d'autre vous concernant. Lorsque la station est choisie pour vous, il s'agit de la station la plus proche de vous.

Comme pour toute connexion à Internet, une requête parvient à notre service avec l'adresse IP de votre appareil, nécessaire pour renvoyer la réponse. Nous ne conservons aucun journal des requêtes ni des adresses IP, et nous ne les utilisons pas pour identifier ou suivre qui que ce soit. Cloudflare traite ces données de connexion pour notre compte afin de fournir et de protéger le service, conformément à sa politique de confidentialité : <https://www.cloudflare.com/privacypolicy/>

Île-de-France Mobilités ne reçoit des requêtes que de notre service, jamais de votre appareil ; elle ne voit donc pas votre adresse IP.

## Services Apple (iPhone et iPad)

La vue en RA utilise les ancres de localisation d'ARKit (géolocalisation, « geotracking »). Pour aligner la scène, ARKit télécharge les données de localisation d'Apple Plans pour la zone où vous vous trouvez et les compare à l'image de la caméra sur votre appareil. Apple indique qu'aucune image de la caméra n'est envoyée à Apple. La carte en direct est Apple Plans (MapKit).

Apple peut collecter des données par l'intermédiaire de ces services, de l'App Store et de TestFlight, comme décrit dans sa politique de confidentialité : <https://www.apple.com/legal/privacy/>

## Services Google (Android)

Sur Android, l'Application fonctionne avec les Services Google Play pour la RA (ARCore), fournis par Google et régis par les Règles de confidentialité de Google. La vue en RA utilise l'API Geospatial d'ARCore pour déterminer précisément l'endroit où vous vous trouvez : pour faire fonctionner cette session, Google traite des données de capteurs (comme la caméra et la localisation). Google explique comment les Services Google Play pour la RA traitent vos données ici : <https://support.google.com/ar?p=how-google-play-services-for-ar-handles-your-data>

La carte en direct est Google Maps (SDK Maps pour Android).

Google peut collecter des données par l'intermédiaire de ces services et de Google Play, comme décrit dans ses règles de confidentialité : <https://policies.google.com/privacy>

## Versions bêta

Si vous testez une version bêta via TestFlight, Apple nous communique certaines informations : les rapports de plantage et les informations d'utilisation de la bêta, vos nom et adresse e-mail si nous vous avons invité par e-mail (pas si vous avez rejoint la bêta par un lien public), ainsi que les commentaires et captures d'écran que vous choisissez d'envoyer. Apple explique le traitement des données par TestFlight ici : <https://www.apple.com/legal/privacy/data/en/test-flight/>

Si vous testez une version préliminaire via Google Play, nous connaissons l'adresse e-mail que nous avons ajoutée à la liste des testeurs, et nous recevons les commentaires que vous choisissez d'envoyer.

Nous utilisons ces informations uniquement pour tester et améliorer l'Application, et nous ne les partageons avec personne.

## Rapports de plantage et de performances

Apple et Google peuvent nous transmettre des rapports de plantage et de performances de l'Application provenant de personnes ayant activé le partage des diagnostics dans les réglages de leur appareil. Ces rapports décrivent le problème et le type d'appareil, pas votre identité. Nous les utilisons uniquement pour corriger les problèmes de l'Application.

## E-mail

Si vous nous écrivez, nous recevons votre adresse e-mail et votre message, et nous les utilisons uniquement pour vous répondre. Nous les supprimons sur demande.

## Autorisations

L'Application vous demandera l'autorisation d'utiliser :

**La caméra** - nécessaire pour la vue en RA.

**La position** - nécessaire pour placer les trains autour de vous et trouver la station la plus proche. Sur iPhone et iPad, elle est aussi utilisée par le mode « station la plus proche » du widget.

Vous pouvez les modifier à tout moment : sur iPhone et iPad dans Réglages, sous Subwhere ; sur Android dans Paramètres, sous Applications, Subwhere, Autorisations.

## Vos droits

AppLand est responsable des données personnelles décrites dans la présente politique. Lorsque nous en traitons (les données de connexion, les informations des versions bêta, les rapports de plantage et les e-mails décrits ci-dessus), c'est parce que cela est nécessaire pour faire fonctionner, tester et assister l'Application. Nous conservons si peu de données qu'il n'y a généralement rien à consulter, corriger ou supprimer, mais vous pouvez nous interroger à ce sujet à l'adresse ci-dessous.

Si vous vous trouvez dans l'UE ou au Royaume-Uni, vous pouvez également introduire une réclamation auprès d'une autorité de protection des données : en Suède, où AppLand est établie, l'Autorité suédoise de protection de la vie privée (IMY) ; en France, la Commission nationale de l'informatique et des libertés (CNIL) ; au Royaume-Uni, l'Information Commissioner's Office (ICO).

## Enfants

L'Application ne s'adresse pas aux enfants de moins de 13 ans, et elle ne collecte de données personnelles auprès de personne.

## Modifications de la présente politique

Si nous modifions la présente politique, nous mettrons à jour la date de « Dernière mise à jour » ci-dessus.

## Contact

Des questions ? Écrivez à <applandapps@gmail.com>.

---

# Privacy Policy for Subwhere Paris

Last updated: 15 October 2026

This Privacy Policy describes how Subwhere Paris ("Subwhere" on your Home Screen; "the App", "we", "us") handles information when you use the App and its widgets on iOS and Android.

Subwhere Paris is published by AppLand (Stefan Almqvist), based in Sweden.

Contact: <applandapps@gmail.com>

## Short version

The App does not collect personal data. There are no accounts, no analytics, no advertising and no tracking. Your location and your camera image are never sent to us. To show live trains, the App downloads Métro data through a small service we run. Those requests contain no account, no identifier and no location coordinates, and we keep no record of them. The augmented reality view uses Apple's or Google's AR services, which handle data as described under "Apple services" and "Google services".

## What the App uses on your device

**Camera feed.** Used by your device's augmented reality framework (Apple's ARKit on iPhone and iPad, Google Play Services for AR on Android) to show the augmented reality view and to recognise the buildings around you, so the trains line up with the street. The App never records, saves or sends the camera image to us. On Android, Google processes camera data to power the AR session (see "Google services").

**Location.** Used to place trains relative to where you are standing, to find your nearest station and point the way to it, and on iPhone and iPad to choose the station the widget shows. The App uses your location on your device. It is never sent to us, never stored as a location history, and never shared or sold. On Android, Google processes location data to power the AR session (see "Google services").

**Device motion and compass heading.** Used for the AR view and the station compass. Processed on your device only.

**Data kept on your device.** So the widget can work without opening the App, the App keeps the names of the Métro stations and their platforms, the latest departures for your nearest station and your widgets' stations, and the day's timetables of recent nearest and chosen stations. It also remembers your language choice and whether you have seen the introduction. None of this is sent to us, and it is deleted when you delete the App.

We do not use analytics, tracking SDKs, advertising, crash-reporting services or any other third-party data collection. The App does not use an advertising identifier and does not track you across other companies' apps or websites.

## Widgets

Subwhere Paris offers optional widgets that show upcoming departures.

On iPhone and iPad, the Home Screen and Lock Screen widgets show either a station you choose or, by default, the station nearest you. To find the nearest station a widget reads your device's location on your device, including while the App is closed. As in the App, your location is used only on your device to work out which station is nearest. It is never stored as a history, sent to us, shared or sold.

On Android, the home-screen widget shows a station you choose. It does not use your location.

## Live train data

Departures, train predictions, timetables and traffic information come from the open data of Île-de-France Mobilités, published on its PRIM platform. The App does not contact Île-de-France Mobilités itself. It asks a small service that AppLand runs on Cloudflare, which fetches the data from PRIM, stores it and passes it on. This keeps our PRIM access key out of the App and the load on PRIM low. Subwhere Paris is not affiliated with or endorsed by Île-de-France Mobilités or RATP.

These requests contain no account, no device identifier and no location coordinates. Most ask for the predictions for the whole network or the traffic information for every line, which are the same for everyone. When the App or a widget needs departures or the timetable for a single station, the request names that station's platforms and nothing else about you. When the station is picked for you, it is the station nearest you.

Like any internet connection, a request reaches our service with your device's IP address, which is needed to send the answer back. We do not keep logs of requests or IP addresses, and we do not use them to identify or follow anyone. Cloudflare processes this connection data on our behalf to deliver and protect the service, under its privacy policy: <https://www.cloudflare.com/privacypolicy/>

Île-de-France Mobilités receives requests only from our service, never from your device, so it does not see your IP address.

## Apple services (iPhone and iPad)

The AR view uses Apple's ARKit location anchors (geotracking). To line up the scene, ARKit downloads Apple Maps localisation data for the area you are in and matches it against the camera image on your device. Apple states that no camera images are sent to Apple. The live map is Apple Maps (MapKit).

Apple may collect data through these services, the App Store and TestFlight as described in its privacy policy: <https://www.apple.com/legal/privacy/>

## Google services (Android)

On Android, the App runs on Google Play Services for AR (ARCore), which is provided by Google and governed by the Google Privacy Policy. The AR view uses ARCore's Geospatial API to find exactly where you are standing: to power this session, Google processes sensor data (such as camera and location). Google explains how Google Play Services for AR handles your data here: <https://support.google.com/ar?p=how-google-play-services-for-ar-handles-your-data>

The live map is Google Maps (Maps SDK for Android).

Google may collect data through these services and Google Play as described in its privacy policy: <https://policies.google.com/privacy>

## Beta testing

If you test a beta version through TestFlight, Apple shares some information with us: crash logs and usage information from the beta, your name and email address if we invited you by email (not if you joined through a public link), and any feedback and screenshots you choose to send. Apple explains TestFlight's data handling here: <https://www.apple.com/legal/privacy/data/en/test-flight/>

If you test a pre-release version through Google Play, we know the email address we added to the tester list, and we receive any feedback you choose to send.

We use this information only to test and improve the App, and we do not share it with anyone.

## Crash and performance reports

Apple and Google may give us crash and performance reports about the App from people who have turned on diagnostics sharing in their device settings. These reports describe the problem and the type of device, not who you are. We use them only to fix problems in the App.

## Email

If you email us, we receive your email address and your message, and use them only to reply. We delete them on request.

## Permissions

The App will ask for permission to use:

**Camera** - needed for the AR view.

**Location** - needed to place trains around you and to find your nearest station. On iPhone and iPad it is also used by the widget's nearest-station mode.

You can change these at any time: on iPhone and iPad in Settings under Subwhere, and on Android in Settings under Apps, Subwhere, Permissions.

## Your rights

AppLand is responsible for the personal data described in this policy. Where we handle any (the connection data, beta testing information, crash reports and emails described above), we do so because it is needed to run, test and support the App. We keep so little that there is usually nothing for us to access, correct or delete, but you can ask us about any of it at the address below.

If you are in the EU or the UK, you can also complain to a data protection authority: in Sweden, where AppLand is based, the Swedish Authority for Privacy Protection (IMY); in France, the Commission nationale de l'informatique et des libertés (CNIL); in the UK, the Information Commissioner's Office (ICO).

## Children

The App is not directed at children under 13, and it does not collect personal data from anyone.

## Changes to this policy

If we change this policy, we will update the "Last updated" date above.

## Contact

Questions? E-mail <applandapps@gmail.com>.
