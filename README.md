# basicintegramp
Integrating Ramp Instant in hosted mode is pretty straightforward - the only thing you need to do is to redirect your user to https://buy.ramp.network/. 


If you use npm or yarn, run:

# npm
$ npm install @ramp-network/ramp-instant-sdk

# yarn
$ yarn add @ramp-network/ramp-instant-sdk
You can also use a CDN and a script tag. You can learn how to use this method here.

A basic example looks like this:

new RampInstantSDK({
  hostAppName: 'Maker DAO',
  hostLogoUrl: 'https://cdn-images-1.medium.com/max/2600/1*nqtMwugX7TtpcS-5c3lRjw.png',
}).show();


If you use Hosted Mode

<a href="https://buy.ramp.network/" target="_blank">Go to Ramp Instant</a>

For example, let's set a userAddress param so that it'll be prefilled for the user.

<a
  href="https://buy.ramp.network/?userAddress=user blockchain address"
  target="_blank"
>
  Go to Ramp Instant
</a>
