# Module 5: Invoke the HTTP API from the browser

In this last module, you will you will use browser to invoke the HTTP API you created in the previous module.

## Invoke the HTTP API

You will use the ReqBin website to send inference requests from your browser to the HTTP API you created. 

1. Go to https://reqbin.com/

2. Configure the client as shown in the following screenshot:

    <img src="../images/module_05/reqbin.png" alt="Invoke API from the browser" />

    Make sure you:
    - Provide the address of the Amazon API Gateway API you deployed in the previous module.
    - Set the method to POST.
    - Set the content type to text/plain.
    - Add an inference record as content. Example: 

    ```L, 298.4, 308.2, 1582, 70.7, 216```

3. Choose **Send** to execute the request and get the inference result.

## You have completed the workshop!

We hope you have enjoyed the journey. In this workshop, you followed an experimentation process in SageMaker Studio using a JupyterLab space and built and trained a model. You then used SageMaker Studio's Code Editor, which is based on Code-OSS, to deploy the model on a SageMaker inference endpoint. You then built a SageMaker Pipeline to automate the complete process, and created an HTTP API to allows web clients to perform predictions.

Please feel free to contiunue exploring the SageMaker Studio environment and reading the notes in the notebooks you might have skipped when going through the modules.

## Clean up
### AWS-run event using AWS Workshop Studio
AWS Workshop Studio performs the clean up after the event, so you don't need to clean up the resources.

### Self-paced using your AWS account
Follow the [clean up steps](../cleanup/README.md) to avoid incurring costs when you no longer require the resources.


## Additional resources
- [What is Amazon SageMaker](https://aws.amazon.com/sagemaker/?nc2=h_ql_prod_ml_sm)
- [Amazon SageMaker FAQs](https://aws.amazon.com/sagemaker/faqs/?nc=sn&loc=4)
- [Amazon SageMaker documentation](https://docs.aws.amazon.com/sagemaker/)
- [Amazon SageMaker developer guide](https://docs.aws.amazon.com/sagemaker/latest/dg/whatis.html)
- [Amazon SageMaker sample notebooks](https://github.com/aws/amazon-sagemaker-examples/blob/main/README.md)