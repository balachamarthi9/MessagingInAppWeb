<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DDd000000191e',
				'PS_MIAW_Humira',
				'https://pap--miawpoc.sandbox.my.site.com/ESWPSMIAWHumira1746614592259',
				{
					scrt2URL: 'https://pap--miawpoc.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://pap--miawpoc.sandbox.my.site.com/ESWPSMIAWHumira1746614592259/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
