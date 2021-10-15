# CHANGELOG

## [Unreleased]

## [Released]

## [1.4.0] - 2021-10-15
### Added
- 80756: new policy (*.userway.org for img-src)
- 82815: new policy:
    - img-src: verify.authorize.net *.affirm.com *.routeapp.io
    - script-src: www.klarnapayments.com *.affirm.com *.routeapp.io
    - style-src: www.klarnapayments.com
    - connect-src: *.affirm.com *.route.com
    - frame-src: *.affirm.com
- 82762:
    - img-src: scontent.cdninstagram.com
    - connect-src: graph.instagram.com

## [1.3.2] - 2021-06-10
### Fixed
- 79029: The Content-Security-Policy directive `frame-ancestors` does not support the source expression `unsafe-inline`
## [1.3.1] - 2021-06-10
### Added
- 79029: new policy (www.paypalobjects.com for frame-src)
## [1.3.0] - 2021-06-10
### Added
- 79029: new policies (www.paypalobjects.com, *.livechatinc.com, *.amazonaws.com, *.kaptcha.com, *.stamped.io, *.userway.org)
## [1.2.0] - 2021-04-21
### Added
- 77649: new policies (pay.google.com, braintree-api.com, braintreegateway.com, tst.kaptcha.com)

## [1.1.0] - 2021-04-08
### Added
- 77278: new policies (gstatic, cloudfront, stamped, zdassets, inspectlet, livechatinc, zendesk, zopim, google, userway, paypal, braintree)

## [1.0.0] - 2021-03-23
- Initial release
