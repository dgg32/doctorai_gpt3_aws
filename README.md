# doctorai_gpt3_aws

Set up an r4.large instance on EC2 with Neo4j community running. It assumes that you have a key called "cloudformation". If you have the key in other name, you can change it in Line 37.

## build
sam build

## deployment
sam deploy --guided --capabilities CAPABILITY_NAMED_IAM

## destruction
sam delete --stack-name doctorai

## Authors

  

*  **Sixing Huang** - *Concept and Coding*

  

## License

  

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
