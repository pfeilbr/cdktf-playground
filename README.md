# cdktf-playground

learn cdktf.  based on [Build AWS Infrastructure with TypeScript](https://learn.hashicorp.com/tutorials/terraform/cdktf-build)

## Notes

* cdktf generates tf hcl json
* cdktf synth creates `cdktf.out`

## Demo

```sh
cdktf init --template=typescript --local

# add aws provider to `cdktf.json` // "hashicorp/aws@~> 3.42"

# creates `.gen` folder which is codegend .ts
cdktf get

# edit `main.ts`

# deploy
cdktf deploy

# clean up
cdktf destroy
```

**Directory Structure**

![](https://www.evernote.com/l/AAGimu-wZYVBPoSWHzvmMRQVCtMkRE0DLMEB/image.png)

**Deploy Output**

![](https://www.evernote.com/l/AAEg6JEtPxJIo67G-wcFzSwLsaBDhB0XJY0B/image.png)

**Destroy Output**

![](https://www.evernote.com/l/AAEyX839eA1MEKGxcifO5JRrYcMGv_ibG58B/image.png)

## Resources

* [Write CDK for Terraform configurations](https://learn.hashicorp.com/collections/terraform/cdktf)
