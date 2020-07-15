# jenkins-hello-world-plugin
This plugin performs two things:
1. Prints the message provided in the freestyle job configuration to the console output.
2. Displays the message on a separate page accessible via the left side panel.

## Build and run the plugin
1. Clone this repository.
2. On the command line, run `mvn hpi:run`. This builds the plugin.
3. Wait until you see the message `INFO: Jenkins is fully up and running`.
3. On you browser, go to `http://localhost:8080/jenkins/`.
4. Create a new freestyle job.
5. In the job configuration page, go to **Build** > **Add build step** > **Say hello world**. 
6. In the **Name** field, type a message or any text.
7. Click **Save**.
8. On the left side panel, click **Build Now**.

The specified message appears in the following locations under **Build History** > **\[#BUILD NUMBER\]**:
- Console Output
- Greeting (the new view)
    

Reference - [Plugin Tutorial - Jenkins](https://www.jenkins.io/doc/developer/tutorial/)