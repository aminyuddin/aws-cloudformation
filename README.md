# aws-cloudformation

Just my personal cloudformation library.

## Usage

```
PROMPT> aws cloudformation create-stack \
--stack-name myteststack \
--template-body file://home/testuser/mytemplate.json \
--parameters ParameterKey=Parm1,ParameterValue=test1 ParameterKey=Parm2,ParameterValue=test2 \
{
  "StackId" : "arn:aws:cloudformation:us-west-2:123456789012:stack/myteststack/330b0120-1771-11e4-af37-50ba1b98bea6"
}
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)