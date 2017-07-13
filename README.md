# Repository

org.eclipse.jgit.api.errors.NoHeadException: Pull on repository without HEAD currently not supported
at org.eclipse.jgit.api.PullCommand.call(PullCommand.java:161)
at com.appvance.enterprise.repository.GitRepositoryController.updatePassword(GitRepositoryController.java:175)
at com.appvance.enterprise.repository.GitRepositoryController.update(GitRepositoryController.java:122)
at com.appvance.enterprise.repository.RepositoryManager.updateConfigurations(RepositoryManager.java:225)
at com.appvance.enterprise.repository.RepositoryManager.run(RepositoryManager.java:261)

9:59
then I click Accepts, and the status goes to: NOT CONFIGURED YET

10:00
then I wait again, try about 3 more times, and eventually the status updates to WORKING
