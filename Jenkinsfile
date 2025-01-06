he recommended git tool is: NONE
using credential Sachin
Cloning the remote Git repository
Cloning with configured refspecs honoured and without tags
Cloning repository https://github.com/sachin0822-byte/login-page-website.git
 > /usr/share/maven init /var/lib/jenkins/workspace/Build-project_main # timeout=10
ERROR: Error cloning remote repo 'origin'
hudson.plugins.git.GitException: Could not init /var/lib/jenkins/workspace/Build-project_main
	at PluginClassLoader for git-client//org.jenkinsci.plugins.gitclient.CliGitAPIImpl$5.execute(CliGitAPIImpl.java:1079)
	at PluginClassLoader for git-client//org.jenkinsci.plugins.gitclient.CliGitAPIImpl$2.execute(CliGitAPIImpl.java:825)
	at PluginClassLoader for git//hudson.plugins.git.GitSCM.retrieveChanges(GitSCM.java:1221)
	at PluginClassLoader for git//hudson.plugins.git.GitSCM._checkout(GitSCM.java:1311)
	at PluginClassLoader for git//hudson.plugins.git.GitSCM.checkout(GitSCM.java:1278)
	at PluginClassLoader for workflow-scm-step//org.jenkinsci.plugins.workflow.steps.scm.SCMStep.checkout(SCMStep.java:136)
	at PluginClassLoader for workflow-scm-step//org.jenkinsci.plugins.workflow.steps.scm.SCMStep$StepExecutionImpl.run(SCMStep.java:101)
	at PluginClassLoader for workflow-scm-step//org.jenkinsci.plugins.workflow.steps.scm.SCMStep$StepExecutionImpl.run(SCMStep.java:88)
	at PluginClassLoader for workflow-step-api//org.jenkinsci.plugins.workflow.steps.SynchronousNonBlockingStepExecution.lambda$start$0(SynchronousNonBlockingStepExecution.java:47)
	at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:539)
	at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:264)
	at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1136)
	at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:635)
	at java.base/java.lang.Thread.run(Thread.java:840)
Caused by: hudson.plugins.git.GitException: Error performing git command: /usr/share/maven init /var/lib/jenkins/workspace/Build-project_main
	at PluginClassLoader for git-client//org.jenkinsci.plugins.gitclient.CliGitAPIImpl.launchCommandIn(CliGitAPIImpl.java:2864)
	at PluginClassLoader for git-client//org.jenkinsci.plugins.gitclient.CliGitAPIImpl.launchCommandIn(CliGitAPIImpl.java:2768)
	at PluginClassLoader for git-client//org.jenkinsci.plugins.gitclient.CliGitAPIImpl.launchCommandIn(CliGitAPIImpl.java:2763)
	at PluginClassLoader for git-client//org.jenkinsci.plugins.gitclient.CliGitAPIImpl.launchCommand(CliGitAPIImpl.java:2052)
	at PluginClassLoader for git-client//org.jenkinsci.plugins.gitclient.CliGitAPIImpl$5.execute(CliGitAPIImpl.java:1077)
	... 13 more
Caused by: java.io.IOException: Cannot run program "/usr/share/maven" (in directory "/var/lib/jenkins/workspace/Build-project_main"): error=13, Permission denied
	at java.base/java.lang.ProcessBuilder.start(ProcessBuilder.java:1143)
	at java.base/java.lang.ProcessBuilder.start(ProcessBuilder.java:1073)
	at hudson.Proc$LocalProc.<init>(Proc.java:252)
	at hudson.Proc$LocalProc.<init>(Proc.java:221)
	at hudson.Launcher$LocalLauncher.launch(Launcher.java:994)
	at hudson.Launcher$ProcStarter.start(Launcher.java:506)
	at PluginClassLoader for git-client//org.jenkinsci.plugins.gitclient.CliGitAPIImpl.launchCommandIn(CliGitAPIImpl.java:2841)
	... 17 more
Caused by: java.io.IOException: error=13, Permission denied
	at java.base/java.lang.ProcessImpl.forkAndExec(Native Method)
	at java.base/java.lang.ProcessImpl.<init>(ProcessImpl.java:314)
	at java.base/java.lang.ProcessImpl.start(ProcessImpl.java:244)
	at java.base/java.lang.ProcessBuilder.start(ProcessBuilder.java:1110)
	... 23 more
ERROR: Error cloning remote repo 'origin'
ERROR: Maximum checkout retry attempts reached, aborting
[Pipeline] }
[Pipeline] // stage
[Pipeline] }
[Pipeline] // node
[Pipeline] End of Pipeline
ERROR: Error cloning remote repo 'origin'

Could not update commit status, please check if your scan credentials belong to a member of the organization or a collaborator of the repository and repo:status scope is selected


GitHub has been notified of this commit’s build result

Finished: FAILURE
