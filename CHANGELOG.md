Version 1.1.0 (2023-08-18)
-----------------------------
* Add support for Tutor 16, Open edX Palm,
  Python versions 3.10 and 3.11.

Version 1.0.0 (2023-07-21)
-----------------------------

* Add a `tutor k8s registry` command for configuring 
  access to a private image registry. 
  Running the command will create imagePullSecret(s)
  and apply them to the `default` ServiceAccount in 
  the given namespace.