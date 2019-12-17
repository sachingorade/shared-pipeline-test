#!/usr/bin/env groovy
// This is a simple change
@Library('steps')
import Singular

boolean additionalFlag = true

// country specific configuration
def countryConfig = new CountryConfig(deployAT: true, deployIN: false)

// overall product specific build config
def productConfig = new ProductConfig(countryConfig: countryConfig)

Singular(productConfig, additionalFlag)
