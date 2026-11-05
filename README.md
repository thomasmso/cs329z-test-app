# cs329z-test-app

Fixture data, not a real app. A copy of the `ios_swift_max_network_missing_admob` fixture from
corvint, used to test the auditor's pull requests through the GitHub App. The versions in the
Podfile are real published versions used as plausible project content, not "latest" claims.

The Podfile is missing the AdMob adapter (`AppLovinMediationGoogleAdapter`) and `Info.plist` has no
`GADApplicationIdentifier`.
