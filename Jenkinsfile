#!/usr/bin/env groovy
// This is a simple change
@Library('steps')
import Singular

def productConfig = new ProductConfig(countryConfig = new CountryConfig(deployAT: true, deployIN: false))

Singular(productConfig)
