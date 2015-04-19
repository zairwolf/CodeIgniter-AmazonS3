# CodeIgniter-AmazonS3

This is for CodeIgniter 3.

**Readme**

1. Install AWS SDK PHP to `/var/www/` via composer: http://docs.aws.amazon.com/aws-sdk-php/guide/latest/installation.html.
2. Upload S3.php to CodeIgniter library folder `/application/libraries/S3.php`.
3. Upload s3config.php to CodeIgniter config folder `/application/config/s3config.php`, then change the key&secret&bucket in this file to your own.
4. Use `$this->load->library('s3');echo $this->s3->read('yourFileOnBucket.txt');` to test it.
5. Enjoy it.

**About**

a simple library for CodeIgniter to operate Amazon S3 files

Enjoy PHP together.
