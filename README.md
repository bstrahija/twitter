# Twitter Helper

Just a simple helper to fetch tweets from a user.

The tweets are cached with the CI cache library. Just set it up as you want in the configuration.

## Usage

	Twitter::timeline('strija', 10);
	
Or

	Twitter::timeline_list('strija', 10);
