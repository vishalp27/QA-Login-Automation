# Watir-Selenium Scripts

Example

require 'watir'

browser = Watir::Browser.new

browser.goto 'watir.com'
browser.link(text: 'Documentation').click

puts browser.title
browser.close

Watir also known as Web Application Testing in Ruby is an API which is powered by Selenium. It uses WatirSpec for testing. The above information is quoted from https://github.com/watir/watir

You can find more details about Watir by going:

    http://watir.github.io
    http://github.com/jarib/webidl
    http://github.com/watir/watirspec
    https://github.com/seleniumhq/selenium

I have been researching on other Test Automation Framework, but I found Watir to be most reliable and so far the best Automation Framework. It integrates all its test with rspec framework, where a Tester can write his own Automation Test Suite based on the BDD ( Acceptance User Stories) available for their project.

To execute, rspec scripts, you can use Sublime Text and then run from cmd, if you already have Ruby dev env setup on your machine. Also, I personally find Rubymine is good when compare to other IDE, to execute the rspec test. 

I am still new to Watir, so research on this has always fascinated me. More to come..
