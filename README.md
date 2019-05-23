# udacity-aws-website-demo

Static website and resources for Udacity teaching demo.

The hosted demo website can be found here: http://codeschwert-udacity-demo.s3-website-ap-southeast-2.amazonaws.com/

## Globe Website - `webgl-globe`

The Globe static webpage in the `/public` folder is a modified Google Chrome experiment created by the Google Data Arts Team. The original code can be found here: 

- Github repo: https://github.com/dataarts/webgl-globe
- Chrome Experiments: https://experiments.withgoogle.com/chrome/globe
- Globe live demo: http://globe.chromeexperiments.com/

The `index.html` file needed to be moved to the top level for the relative `/global` URL paths to work correctly.

## AWS S3 Bucket Policy

Remember to change the `arn` in the `policy.json` file!! It's currently set to `example-bucket`
