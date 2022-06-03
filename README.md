Usage
---- 
- Add elb_health_check to INSTALLED_APPS.
- Add elb_health_check.middleware.ELBHealthCheckMiddleware to MIDDLEWARE.

Example::

    INSTALLED_APPS.append("elb_health_check")
    MIDDLEWARE.insert(0, "elb_health_check.middleware.ELBHealthCheckMiddleware")
