## v0.6.0-beta1

Usage:

- Add `Alipay.sign_type`, default is 'MD5', 'RSA' and 'DSA' will implemented in the future.
- Remove `Sign::App.verify?`, use `Sign.verify_rsa?` instead.
- Remove `Notify::App.verify?`, use `Notify.verify?` instead.
- Rename `Service::Wap.auth_and_execute` to `Service::Wap.auth_and_execute_url`

Development:

- Update Test::Unit to Minitest.
- Fxied test case data.

## v0.5.0 (2015-03-09)

- Add `forex_single_refund` service.
- Add `debug_mode` config:

  set `Alipay.debug_mode = false` to disable options check warning in production env.

## v0.4.1 (2015-03-03)

- Fix `single_trade_query` check options typo.

## v0.4.0 (2015-01-23)

- Add `single_trade_query` service. #19

## v0.3.1 (2015-01-15)

- Fix xml encoding #18

## v0.3.0 (2014-12-10)

- Add `close_trade` service. by @linjunpop #16

## v0.2.0 (2014-12-03)

- Add `create_forex_trade` service. by @christophe-dufour #15

## v0.1.0 (2014-06-15)

- Add Wap API by @HungYuHei

- Add App API by @HungYuHei
