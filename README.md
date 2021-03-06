# File Uploads on AWS Bucket

## Description :clipboard:
> Demo App for Single and Multiple File Uploads on AWS ( Amazon Web Services ) Bucket




## Use :point_right:

Update your AWS accessKeyId, secretAccessKey and Bucket name in `./routes/api/profile.js`

``` ruby
const s3 = new aws.S3({
	accessKeyId: 'xxx',
	secretAccessKey: 'xxx',
	Bucket: 'yourbucketname'
});

```

## Installation Instructions :wrench:

1. Clone the repo using `git clone https://github.com/imranhsayed/file-uploads-aws-react-node`
2. `cd file-uploads-aws-react-node`
3. `npm install`
4. `cd client`
5. `npm install`
7. `cd ..`

8. Update your AWS accessKeyId, secretAccessKey and Bucket name in `./routes/api/profile.js`

``` ruby
const s3 = new aws.S3({
	accessKeyId: 'xxx',
	secretAccessKey: 'xxx',
	Bucket: 'yourbucketname'             //line 15
});
		
		
		
		bucket: 'yourbucketname',     //line  24



9.  change access to bucket to public
10. `npm run dev`

## Built With :zap:

1. Node
2. Express
3. React
4. Create React App


## Useful Links :link:

* [Create AWS Bucket Blog](https://codeytek.com/how-to-create-a-user-and-bucket-amazon-web-services-aws/)
* [File Upload on AWS Blog](https://codeytek.com/file-or-image-uploads-on-amazon-web-services-aws-using-react-node-and-express-js-aws-sdk/)

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
