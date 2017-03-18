@Library('SQE-CI') _

def slack_channel = "#eugeun-ci"
def failed = false

node {
    sendNotifications {
        isFailed = failed
        slackChannel = slack_channel
        slackCustomMsg = "Test"
    }
}

