<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://www.pubnub.com/integrations/amazon-lex-build-conversation-bots/" target="_blank">
    <img src="images/logo_lex.jpeg" alt="Amazon Lex" width="80" height="80">
  </a>

  <h3 align="center">Amazon Lex Build Conversation Bots with PubNub</h3>

  <p align="center">
    Conversational interfaces for your applications powered by the same deep learning technologies as Alexa with PubNub.
    <br />
    <a href="https://www.pubnub.com/integrations/amazon-lex-build-conversation-bots/" target="_blank"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://www.pubnub.com/tour/introduction/" target="_blank">View Demo</a>
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project

This projects uses PubNub chat feature with Amazon Lex integration to trigger actions like extend a reservation, request a refund, contact support. The Alexa use a dialog model to identify the prompts and user utterances to collect, validate, and confirm slot values and intents.

<a href="https://www.pubnub.com/integrations/amazon-lex-build-conversation-bots/" target="_blank">
    <img src="images/AWS-Lex-and-PubNub-Architecture.png" alt="Architecture by Saulo Stopa" >
</a>

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

This section list the major frameworks/libraries/services used to bootstrap this project.

* [AWS]()
* * [Alexa](https://developer.amazon.com/en-US/docs/alexa/smapi/send-a-message-request-to-a-skill.html)
* * * [Delegate Dialog](https://developer.amazon.com/en-US/docs/alexa/custom-skills/delegate-dialog-to-alexa.html)
* * * [Validation Slot Values](https://developer.amazon.com/en-US/docs/alexa/custom-skills/validate-slot-values.html#configure)
* * * [Interaction Model Scheme](https://developer.amazon.com/en-US/docs/alexa/smapi/interaction-model-schema.html)
* * * [Add Card to the Reservation or Refund](https://developer.amazon.com/en-US/docs/alexa/custom-skills/include-a-card-in-your-skills-response.html)
* * [Cognito](https://docs.aws.amazon.com/cognito/latest/developerguide/what-is-amazon-cognito.html)
* * [IAM Policy for](https://aws.amazon.com/iam/)
* * * AWSLambdaBasicExecutionRole
* * * AWSXRayDaemonWriteAccess
* * * AmazonDocDBReadOnlyAccess
* * * AmazonDocDBFullAccess
* * * AmazonDocDBConsoleFullAccess
* * [Lambda Function](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)
* * * [VPC](https://docs.aws.amazon.com/lambda/latest/dg/configuration-vpc.html)
* [PubNub Integration for Amazon Lex](https://www.pubnub.com/integrations/amazon-lex-build-conversation-bots/)
* [Node.js](https://nodejs.dev/)

<p align="right">(<a href="#top">back to top</a>)</p>
