The behavior can be configured and customized on the Flow "Update all ServiceNow Applications".

Important hints:
- The Credential Alias "sn_cicd_spoke.CICD" needs a working Credential for the target instance. This is also important if you want to modify the Flow for targeting other instances.
- If you wonder how the Store Application table was added to the Flow: glide.ui.permitted_tables needs to have sys_store_app to be included.
