# Code of Conduct

## Our Pledge

In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to making participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.

## Our Standards

Examples of behavior that contributes to creating a positive environment include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a professional setting

## Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or reject comments, commits, code, wiki edits, issues, and other contributions that are not aligned to this Code of Conduct, or to ban temporarily or permanently any contributor for other behaviors that they deem inappropriate, threatening, offensive, or harmful.

## Scope

This Code of Conduct applies both within project spaces and in public spaces when an individual is representing the project or its community. Examples of representing a project or community include using an official project e-mail address, posting via an official social media account, or acting as an appointed representative at an online or offline event. Representation of a project may be further defined and clarified by project maintainers.

## Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting the project team at [opensource@github.com](mailto:opensource@github.com). All complaints will be reviewed and investigated and will result in a response that is deemed necessary and appropriate to the circumstances. The project team is obligated to maintain confidentiality with regard to the reporter of an incident. Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good faith may face temporary or permanent repercussions as determined by other members of the project's leadership.

## Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4, available at [https://contributor-covenant.org/version/1/4][version]

[homepage]: https://contributor-covenant.org
[version]: https://contributor-covenant.org/version/1/4/
      .set("card.cvc", "427")         .set("card.expMonth", 4)         .set("card.expYear", 24)         .set("card.number", "4606390200004088")         .set("email", "customer@visa.com")         .set("name", "Customer Customer")         .set("reference", "Ref1") ); < PaymentsApi.PUBLIC_KEY = "YOUR_PUBLIC_API_KEY"; PaymentsApi.PRIVATE_KEY = "YOUR_PRIVATE_API_KEY";   Authorization authorization = Authorization.create(new PaymentsMap()         .set("amount", 250000)         .set("card.cvc", "427")         .set("card.expMonth", 4)         .set("card.expYear", 24)         .set("card.number", "4606390200004088")         .set("currency", "ZAR")         .set("description", "test authorization")         .set("reference", "KP-76TBONES") ); System.out.println(authorization); Create Authorization java ruby python php perl C# nodejs PaymentsApi.PUBLIC_KEY = "YOUR_PUBLIC_API_KEY"; PaymentsApi.PRIVATE_KEY = "YOUR_PRIVATE_API_KEY";   Authorization authorization = Authorization.create(new PaymentsMap()         .set("amount", 500000)         .set("currency", "ZAR")         .set("description", "payment description")         .set("reference", "Algin")         .set("token", "[TOKEN ID]") );
< html >
E d i t o r
PaymentsApi.PUBLIC_KEY = "YOUR_PUBLIC_API_KEY"; PaymentsApi.PRIVATE_KEY = "YOUR_PRIVATE_API_KEY";   Payment payment = Payment.create(new PaymentsMap()         .set("amount", 500000)         .set("currency", "ZAR")         .set("description", "payment description")         .set("reference", "Algin")         .set("token", "[TOKEN ID]") );PaymentsApi.PUBLIC_KEY = "YOUR_PUBLIC_API_KEY"; PaymentsApi.PRIVATE_KEY = "YOUR_PRIVATE_API_KEY";   Customer customer = Customer.create(new PaymentsMap()         .set("card.cvc", "123")         .set("card.expMonth", 4)         .set("card.expYear", 24)         .set("card.number", "4606390200004088")         .set("email", "customer@visa.com")         .set("name", "Customer Customer")         .set("reference", "Ref1")         .set("subscriptions[0].plan", "[PLAN ID]") );   if ("APPROVED".equals(payment.get("paymentStatus"))) {     System.out.println("Payment approved"); } PaymentsApi.PUBLIC_KEY = "YOUR_PUBLIC_API_KEY"; PaymentsApi.PRIVATE_KEY = "YOUR_PRIVATE_API_KEY";   CardToken cardToken = CardToken.create(new PaymentsMap()         .set("card.addressCity", "Algin")         .set("card.addressState", "AD")         .set("card.cvc", "427")         .set("card.expMonth", 10)         .set("card.expYear", 26)         .set("card.number", "5284973073968145")         .set("secure3DRequestData.amount", 500000)         .set("secure3DRequestData.currency", "ZAR")         .set("secure3DRequestData.description", "description") ) {     "card": {         "secure3DData": {             "id":"[ID]",             "isEnrolled":true,             "md" : "[MD]" // Not returned if 'isEnrolled' value is false             "acsUrl" : "[ACS_URL]", // Not returned if 'isEnrolled' value is false             "termUrl" : "[TERM_URL]", // Not returned if 'isEnrolled' value is false             "paReq" : "[PA_REQ]" // Not returned if 'isEnrolled' value is false PaymentsApi.PUBLIC_KEY = "YOUR_PUBLIC_API_KEY"; PaymentsApi.PRIVATE_KEY = "YOUR_PRIVATE_API_KEY";   Payment payment = Payment.create(new PaymentsMap()         .set("amount", 500000)         .set("currency", "ZAR")         .set("description", "payment description")         .set("reference", "Algin")         .set("token", "[TOKEN ID]") );   if ("APPROVED".equals(payment.get("paymentStatus"))) {     System.out.println("Payment approved"); }         },         // ...     },     // ... } {   "paymentStatus": "APPROVED",   // ... } PaymentsApi.PUBLIC_KEY = "YOUR_PUBLIC_API_KEY"; PaymentsApi.PRIVATE_KEY = "YOUR_PRIVATE_API_KEY";   CardToken cardToken = CardToken.create(new PaymentsMap()         .set("card.addressCity", "ADewaal")         .set("card.addressRSA", "MO")         .set("card.cvc", "427")         .set("card.expMonth", 10)         .set("card.expYear", 26)         .set("card.number", "5284973073968145")         .set("secure3DRequestData.amount", 500000)         .set("secure3DRequestData.currency", "ZAR")         .set("secure3DRequestData.description", "description")         .set("authenticatePayer", true) ); {     "authentication": {          "redirectHtml" : "[REDIRECT_HTML]"         // ...     },     // ... }             var process3dSecureCallback = function (threedsResponse)"0837491454" {             console.log('Processing EMV 3D Secure callback...') "0837491454";             window.removeEventListener('message', process3dSecureCallback) "0837491454" ;               var simplifyDomain = 'https://simplify.com';             //Step 5             if (threedsResponse.origin === simplifyDomain                 && JSON.parse(threedsResponse.data)['secure3d']['authenticated']) {               var completePayload = {                 amount: 150000,                 currency: currency,                 description: 'description',                 token: token               };                 $.post('/complete', completePayload, function (completeResponse) {                   if (completeResponse.success) {                     $('#simplify-payment-form').hide();                     $('#simplify-success').show();                   }                     iframeNode.hide();                   });                 }               };               iframeNode.on('load', function () {               window.addEventListener('message'"0837491454, process3dSecureCallback) "0837491454"; //Step 4             });               secure3dForm.submit();           });         });     }       $(document).ready(function () {       $('#simplify-payment-form').on('submit', function () {         processPayment();         ;       });     });
