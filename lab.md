# Helm Lab

In this lab you will continue where we left off in the last lab of kubernetes, where you were tasked with building a wordpress application.

*Make sure to get a working application for lab 3 before continuing. If you want one - ask the instructor for a lab-3 solution or use your own*

In this lab your job is to create a new helm chart of your own that replicates your solution to the previous lab.

Your new chart should have the values.yml (default) with values equal to the requirements in the lab-3. They should be exposed and able to be overwritten.

This includes the adding of additional labels, database password, and image versions.

- You should use commands like `helm lint` `debug` and `--dry-run` to validate your new chart
- You should visit other helm charts for reference - the [wordpress](https://github.com/bitnami/charts/tree/master/bitnami/wordpress) chart we deployed will be helpful
- https://github.com/muffin87/helm-tutorial (uses older version of helm)
- https://helm.sh/docs/topics/charts/
- https://helm.sh/docs/helm/helm_create/
- https://helm.sh/docs/chart_template_guide/


The ending state should be a helm chart that can be installed successfully with the default values and allow for values to be overriden.


**for extra practice** - Make another additional chart that behaves similar - but uses an external chart for the mysql database.


**notes**
- the default version of mysql/wordpress used in the previous lab are not a hard requirement. feel free to use different versions.
