#!/usr/bin/env groovy

properties([ parameters([
  string( name: 'TEST_VALUE', defaultValue: 'World'),
  ])
])

node {
    stage("One") {
        println("Hello ${TEST_VALUE}")
    }
}