# AppCloud updates June 2011

The updates described are either important (where you need to take action) or of interest (you might want to know about these changes but you don't need to do anything). 

---

<a href=#update8><h2 id="update8"> Fix: Automatic snapshot size </h2></a>

June 8th, 2011

Fixed an issue where the snapshot-size text field was not automatically updated when a specific snapshot was selected.

---

<a href=#update7><h2 id="update7"> Fix: Environment update notification </h2></a>

June 8th, 2011

Fixed an issue where some environments were not marked as needing an update.

---

<a href=#update6><h2 id="update6"> Fix: Rubygems 1.5.2 </h2></a>

June 3rd, 2011

Patched a bug fix from June 1st that was causing problems.

---

<a href=#update5><h2 id="update5"> **Major:** High memory XL VM’s available </h2></a>

June 3rd, 2011

You can now create high memory extra-large VM’s in your environment:

* High memory XL (64 bit)

* 6.5 ECU, 17.1GB RAM

* 420GB of non-persistent storage

See [[www.engineyard.com/products/appcloud/pricing|http://www.engineyard.com/products/appcloud/pricing]] for pricing.

---

<a href=#update4><h2 id="update4"> Minor: Environment variables for custom scripts </h2></a>

June 2nd, 2011

If you use custom scripts, your applications now have access to specific stack environment variables. 

You can source /engineyard/bin/env.sh to access these variables: $EY_ENVIRONMENT_NAME, $EY_STACK, $EY_FRAMEWORK_ENV, $RAILS_ENV, $RACK_ENV, and $MERB_ENV.


---

<a href=#update3><h2 id="update3"> Fix: HAproxy restart from single instance snapshot </h2></a>

June 2nd, 2011

Fixed an issue where HAproxy was failing to restart when creating a cluster from a single instance snapshot.

---

<a href=#update2><h2 id="update2"> Fix: Rubygems 1.5.2 update</h2></a>

June 2nd, 2011

Upgrading to rubygems 1.5.2 was breaking Rails applications. This issue was fixed by adding version_requirements back into rubygems 1.5.2.


---

<a href=#update1> <h2 id="update1"> **Major:** X-Forwarded-For SSL traffic enabled </h2></a>

June 2nd, 2011

You can now request Engine Yard Support to enable HTTPS support of X-Forwarded-For via stunneled feature.



[1]: #update1        "update1"
[2]: #update2        "update2"
[3]: #update3        "update3"
[4]: #update4        "update4"
[5]: #update5        "update5"
[6]: #update6        "update6"
[7]: #update7        "update7"
[7]: #update8        "update8"