#!/usr/bin/env groovy
// This is a simple change
@Library('steps')
import Singular

boolean additionalFlag = false

// country specific configuration
def countryConfig = new CountryConfig(deployAT: true, deployIN: false)

// overall product specific build config
def productConfig = new ProductConfig(countryConfig: countryConfig, version: "v1")

Singular(productConfig, additionalFlag)
