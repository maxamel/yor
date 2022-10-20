dHlwIjoiSldUIiwiYWxnIjoiUlMyNTYiLCJraWQiOiJlckk1d25pVWF0X1RoLW9jRC1hZmowd05KVDRBV3RMbDFMMHh1em5NVFgwIn0.eyJzdWIiOiJqZmZlQDAwMC91c2Vycy9oZWxsb0BnaXRndWFyZGlhbi5jb20iLCJzY3AiOiJhcHBsaWVkLXBlcm1pc3Npb25zL2FkbWluIGFwaToqIiwiYXVkIjpbImpmeHJAKiIsImpmbWRAKiIsImpmZXZ0QCoiLCJqZmFjQCoiXSwiaXNzIjoiamZmZUAwMDAiLCJpYXQiOjE2MjE5NzM3NzMsImp0aSI6IjVkOTUxNWZlLTM0ODctNDA2Ny1hNjdmLTYwYmJkNjJhYjcwYiJ9.G142GFb9wZYn3JG4XKTM8PhmvDWpGph1zPl09AIrSGbGOoEJfDmvIWABys65sH4xBQtn6OH6ys0YWg_m1bcsBMGhgBxxYqNjd61UaENmKHjztzWCT-6UPXXqgNLoYE-avqtD6vkxqWQV6tokgTyupyRizhS2TEjfrHNTtIVWi8Q
  host: gitguardian.jfrog.io

- text: >
    const ASANA_AUTHORIZATION = 'Bearer 1/1200301236582917:899755aaa5e57bea70631a524db663e2'
  apikey: 1/1200301236582917:899755aaa5e57bea70631a524db663e2
- text: >
    // OAuth: https://developers.asana.com/docs/oauth
    const token = `1/1175586585180773:bafe862dc1cb6b48a39a2d3a1206a0e6`;
  apikey: 1/1175586585180773:bafe862dc1cb6b48a39a2d3a1206a0e6
- text: >
    curl -H "Authorization: Bearer 1/1198990123456789:d3d1e51e5b2b4f9d9db419f2b084114d" \
    https://app.asana.com/api/1.0/users/me
  apikey: 1/1198990123456789:d3d1e51e5b2b4f9d9db419f2b084114d
- text: >
    #asana
    //1/1198990123456789:d3d1e51e5b2b4f9d9db419f2b084114d
  apikey: 1/1198990123456789:d3d1e51e5b2b4f9d9db419f2b084114d
- text: >
    curl -H "Authorization: Bearer 0/d3d1e51e5b2b4f9d9db419f2b084114d" \
    https://app.asana.com/api/1.0/users/me
  apikey: 0/d3d1e51e5b2b4f9d9db419f2b084114d
- text: >
    #asana
    //0/d3d1e51e5b2b4f9d9db419f2b084114d
  apikey: 0/d3d1e51e5b2b4f9d9db419f2b084114d

- text: >
    oauthEndpoint = oauth2.Endpoint{
    +       AuthURL:  "https://auth.atlassian.com/authorize",
    +       TokenURL: "https://auth.atlassian.com/oauth/token",
    +   }
    +   oauthConfig = &oauth2.Config{
    +       RedirectURL:  "http://localhost:3000/auth/jira/callback",
    +       ClientID:     "W4XTi79CmCvhnWYszR70dypEQFtHA3qH",
    +       ClientSecret: "CXEQC92LBtFAchTsuHnFcf_0if7t8KhFxgM_68dNHKYxZ--n6PwSRFyEckem6X9n",
    +       Scopes:       []string{"read:jira-user", "read:jira-work", "offline_access"},
    +       Endpoint:     oauthEndpoint,
    +   }
    +)

  client_id: W4XTi79CmCvhnWYszR70dypEQFtHA3qH
  client_secret: CXEQC92LBtFAchTsuHnFcf_0if7t8KhFxgM_68dNHKYxZ--n6PwSRFyEckem6X9n

- text: >
    JIRA_CLIENT=s1JWjiFNbAurXIGu2KzSoRD9EF93vjLZ
    JIRA_SECRET=HEJdIgN55jQYZLXDN6hlTJjIjsHms4z0Xtga45XrmLsASTI1X_TE-67VdpwEiv8e

  client_id: s1JWjiFNbAurXIGu2KzSoRD9EF93vjLZ
  client_secret: HEJdIgN55jQYZLXDN6hlTJjIjsHms4z0Xtga45XrmLsASTI1X_TE-67VdpwEiv8e

- text: |
    i=JTvXRY1pCeLp1tyXdDDgk1KyUu1VIXTc
    s=_Yzv7l7Z8DdZ79JfR40JJWhabWSTp5XWFDRuTlGqTLMtMXwzrml81Z5CRpYJ3XSj
    d=gg-test.auth0.com
  domain: gg-test.auth0.com
  client_id: JTvXRY1pCeLp1tyXdDDgk1KyUu1VIXTc
  client_secret: _Yzv7l7Z8DdZ79JfR40JJWhabWSTp5XWFDRuTlGqTLMtMXwzrml81Z5CRpYJ3XSj

- text: |
    "baseuri": "https://api.bing.microsoft.com/v7.0/search",
    "headers": { "Ocp-Apim-Subscription-Key": "bf7ceb0247494d5ea601f15dc63bcaff" },
  apikey: "bf7ceb0247494d5ea601f15dc63bcaff"
- text: |
    `https://api.bing.microsoft.com/v7.0/Suggestions?q=` + value,
    headers: { "Ocp-Apim-Subscription-Key": "775986a0c92a44b996051a3d62f337ff" }
  apikey: "775986a0c92a44b996051a3d62f337ff"
- text: |
    $GLOBALS["subscription_key"] = "66eae5acb8594216b5f07768540e93ff";
    $request = new Http_Request2('https://api.bing.microsoft.com/v7.0/search');
  apikey: "66eae5acb8594216b5f07768540e93ff"

- text: >
    +
    + https://ajC8P25UUCRd5wSFvD:6K2vvBdjQFeas5YXLCup6KtzqBhcK73f@bitbucket.com

  client_id: ajC8P25UUCRd5wSFvD
  client_secret: 6K2vvBdjQFeas5YXLCup6KtzqBhcK73f

- text: |
    -_Environment variable:_ `BUILDKITE_TIMESTAMP_LINES`
     ```sh
     token="45db61df8338027852b24abdf83dd483b016eef98fcd3328e7"
     name="my-app-%n"
    -meta-data="ci=true,docker=true"
    +tags="ci=true,docker=true"
     git-clean-flags="-fdqx"
     debug=true
     ```

  token: 45db61df8338027852b24abdf83dd483b016eef98fcd3328e7

- text: |
    =master
     export BUILDKITE_ACCESS_TOKEN="7a3c5347b067ba89750cc9a513e0d98c4fbfc293"
    +export RUNTIME_DIR=${WORKDIR}/runtime

  token: 7a3c5347b067ba89750cc9a513e0d98c4fbfc293

- text: circleci_token = 63701d3f82137ddaa946945bc950cce674dec53a
  apikey: 63701d3f82137ddaa946945bc950cce674dec53a

- text: >
    curl -X POST url/call-model -d '{"accessKey":"myviox3evmcte97y1zr1cdvnpdntwrn3"}
  apikey: myviox3evmcte97y1zr1cdvnpdntwrn3

- type: FilenameBanlistPreValidator
  banlist_extensions:
  - ^(cs|x|p|s|r|m)?html5?~?$
  - ^[aps]?cssc?~?$
  - ^lock$
  - ^mdx?~?$
  - ^storyboard(c|er)?~?$
  - ^xib$
  banlist_filenames: []
  check_binaries: false
- type: ContentWhitelistPreValidator
  patterns:
  - cloudflare

- text: >
    install:
      - pip install codecov
      - make install

    script:
      - export CODECOV_TOKEN="835a4597-5614-40f5-803c-093464aa2a74"
      - cd test
      - coverage run ./test.py

    after_success:
      - codecov

  apikey: 835a4597-5614-40f5-803c-093464aa2a74
- text: >
    {
      "version": "3.0.0",
      "scripts": {
        "lint": "eslint ./src ./tests",
        "report": "nyc report --reporter=lcov > coverage.lcov && codecov --token=835a4597561440f5803c093464aa2a74",
        "start": "babel-node src/main",
        "test": "tap tests/start.js --coverage --reporter=spec"
      }
    }
  apikey: 835a4597561440f5803c093464aa2a74

- text: confluent
    +# basic.auth.user.info=06R3HSEUIQ1DVO7U:M8m6yxc2AFX8p4IQe8Lf5H+GXmYkGrTSke/J8oCkFqDMs1w65XKASDCdq0RHGVSR
  client_id: 06R3HSEUIQ1DVO7U
  client_secret: M8m6yxc2AFX8p4IQe8Lf5H+GXmYkGrTSke/J8oCkFqDMs1w65XKASDCdq0RHGVSR

- text: fig("spark.databricks.service.token", "dapi12345029efdb94b0cc71fe7118854321"
  token: dapi12345029efdb94b0cc71fe7118854321

- text: |
    stus.azuredatabricks.net
    +login token
    +password dapi12345a25824ee4c246d851e672354321
  token: dapi12345a25824ee4c246d851e672354321

- text: >
    datadog
    key = 3c0c3965368a6b10f7640dbda46abfd2
    secret= 3c0c3965368a6b10f7640dbda46abfdca981c2d3
  client_id: 3c0c3965368a6b10f7640dbda46abfd2
  client_secret: 3c0c3965368a6b10f7640dbda46abfdca981c2d3

- text: >
    DIGITALOCEAN_CLIENT_ID="b378ad25b5a412d112aedeca8c1f8576fb4ccc775055023f41606d358ce520f8"
    DIGITALOCEAN_CLIENT_SECRET="dc01cd6c446bfeea52d48d801197ba3f5242f62469017400f6a206e6b3691025"
  client_id: b378ad25b5a412d112aedeca8c1f8576fb4ccc775055023f41606d358ce520f8
  client_secret: dc01cd6c446bfeea52d48d801197ba3f5242f62469017400f6a206e6b3691025

- text: >
    client = session.client('s3',
                      region_name='ams3',
                      endpoint_url='https://ams3.digitaloceanspaces.com',
                      aws_access_key_id='CO4STQ4XDCGED3PTOJOP',
                      aws_secret_access_key='qh23oFx2boMaQfikW/skdnLL+3/L1Yab4KvuJkXZ5lE')
  client_id: "CO4STQ4XDCGED3PTOJOP"
  client_secret: "qh23oFx2boMaQfikW/skdnLL+3/L1Yab4KvuJkXZ5lE"

- text: >
    dos://CO4STQ4XDCGED3PTOJOP:qh23oFx2boMaQfikW/skdnLL+3/L1Yab4KvuJkXZ5lE@ams3.digitaloceanspaces.com
  client_id: "CO4STQ4XDCGED3PTOJOP"
  client_secret: "qh23oFx2boMaQfikW/skdnLL+3/L1Yab4KvuJkXZ5lE"

- text: knife[:digital_ocean_access_token]  = '710550c7dad844f89c9414db7556e74f3faedf9f5228ab2099c67fa1f2a61f66'
  apikey: 710550c7dad844f89c9414db7556e74f3faedf9f5228ab2099c67fa1f2a61f66
- text: self.digital_ocean_handle.input_access_token("a1a7c625c612c3d9a07300b1396fff2ff129342c63d4516b3101fdb61b1f2a48")
  apikey: a1a7c625c612c3d9a07300b1396fff2ff129342c63d4516b3101fdb61b1f2a48
- text: "be able to edit the file and set the values. The file should look something like this:\n\n    ---\n vault_do_token: 245b743ede8d627b2e7dfbecc7a94711063b6c24ecd65a38f039a24f407bff54\n"
  apikey: 245b743ede8d627b2e7dfbecc7a94711063b6c24ecd65a38f039a24f407bff54
- text: '#define DIGITALOCEAN_CLIENT_SECRET @"245b743ede8d627b2e7dfbecc7a94711063b6c24ecd65a38f039a24f407bff54"'
  apikey: 245b743ede8d627b2e7dfbecc7a94711063b6c24ecd65a38f039a24f407bff54
- text: public $tokenDigitalOcean="6b7ebde6030ce371cafc2266c5450c219d93851d7c12561cf6815440c2e3cb19";
  apikey: 6b7ebde6030ce371cafc2266c5450c219d93851d7c12561cf6815440c2e3cb19
- text: "Bruk denne do_token-en: ea2543dade39ff6f913510cb763ff989f701e668e5ee2a202eee508bb6a80020\n"
  apikey: ea2543dade39ff6f913510cb763ff989f701e668e5ee2a202eee508bb6a80020
