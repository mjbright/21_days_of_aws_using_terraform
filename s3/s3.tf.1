variable s3_bucket_name {
  default = "mjbright"
}

provider "aws" {
  # region = "us-west-2"
  # region unset - use will use AWS_DEFAULT_REGION
}

resource "random_id" "my-random-id" {
  byte_length = 2
}

resource "aws_s3_bucket" "mjbright-test-bucket" {
  #bucket = var.s3_bucket_name
  bucket = "${var.s3_bucket_name}-${random_id.my-random-id.dec}"

  acl = "private"
  versioning {
    enabled = true
  }
  tags =  {
      Name = "21-days-of-aws-using-terraform"
  }
}
