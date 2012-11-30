RubyExample
===========

Feature: Search
   In order to find results
   As a user
   I want to search online

  @search
  Scenario: Search for cucumber
   Given I am on the Google homepage
   When I enter a search for "Cucumber"
   Then I should have results containing "Cucumber"


