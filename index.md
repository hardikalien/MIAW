<html>
	<body>
		<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DNS00000I6Q94',
				'Test_Service',
				'https://orgfarm-d9a2cf9d0b-dev-ed.develop.my.site.com/ESWTestService1745497311555',
				{
					scrt2URL: 'https://orgfarm-d9a2cf9d0b-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://orgfarm-d9a2cf9d0b-dev-ed.develop.my.site.com/ESWTestService1745497311555/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>


	</body>
</html>
