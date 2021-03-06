# Terraform Starter - Snowplow Analytics

## How this was built

You can [follow along with me](https://pragmacoders.com/tag/building-snowplow-analytics-with-terraform/) as I build this!

- [Introduction to Snowplow Analytics](https://pragmacoders.com/introduction-to-snowplow-real-time-analytics/)

- [Part 1 - The Snowplow Collector](https://pragmacoders.com/part-1-the-snowplow-collector/)

- [Part 2 - The Snowplow Stream Enrichment Process](https://pragmacoders.com/part-2-the-snowplow-streaming-enrichment-process/)

## Terraform as Documentation

This repository is intended to be documentation of what a Snowplow (Scala Streaming) stack can look like. It attempts to explicitly state technical specifications of such a stack.

The documentation is written with [Terraform](https://www.terraform.io/)

The documentation is written for [Snowplow Analytics](https://snowplowanalytics.com/)

## Terraform as a Starter

This repository may double as way to quickly create a working Snowplow Analytics stack.

1. `git clone https://github.com/fingerco/snowplow-terraform-starter.git && cd snowplow-terraform-starter`

1. `cp variables.tf.example variables.tf`

1. Modify **variables.tf** to configure everything

1. `terraform init`

1. `terraform plan`

1. `terraform apply`

1. `terraform destroy`

**Note:** Due to the extreme levels of customization that can happen in such a stack, I cannot promise that this setup will fit your exact needs.

I encourage you to look through this, understand it, and modify it as you need.


## Contributions

Feel free to fork this and submit a Pull Request, if you'd like to improve upon it!

You can also become a [patron on Patreon](https://www.patreon.com/coryfinger) if you'd like to free up more of my time to improve this project!
