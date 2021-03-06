=====================================================
|private chef ctl| (executable)
=====================================================

.. warning:: This topic documents the settings for |chef server oec|. The current version of the |chef server| is version 12. All of the documentation at http://docs.getchef.com and http://docs.getchef.com/server/ is about the current version of the |chef server|. The documentation for |chef server oec| has been moved to http://docs.getchef.com/enterprise/ and is archived for specific versions: `Enterprise Chef 11.0 <http://docs.getchef.com/release/oec_11-0/>`__, `Enterprise Chef 11.1 <http://docs.getchef.com/release/oec_11-1/>`__, and `Enterprise Chef 11.2 <http://docs.getchef.com/release/oec_11-1/>`__.

.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef.rst

backup-recover
=====================================================
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_backup_recover.rst

cleanse
=====================================================
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_cleanse.rst

gather-logs
=====================================================
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_gather_logs.rst

ha-status
=====================================================
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_ha_status.rst

help
=====================================================
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_help.rst

master-recover
=====================================================
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_master_recover.rst

password
=====================================================
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_password.rst

reconfigure
=====================================================
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_reconfigure.rst

show-config
=====================================================
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_show_config.rst

uninstall
=====================================================
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_uninstall.rst

upgrade
=====================================================
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_upgrade.rst

**Syntax**

.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_upgrade_syntax.rst

**Options**

.. note:: Options for the ``upgrade`` subcommand may only be used when upgrading from |chef server osc| to |chef server| 12.

.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_upgrade_options.rst

Service Subcommands
=====================================================
|chef server oec| has a built in process supervisor, which ensures that all of the required services are in the appropriate state at any given time. The supervisor starts two processes per service.

hup
-----------------------------------------------------
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_hup.rst

int
-----------------------------------------------------
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_int.rst

kill
-----------------------------------------------------
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_kill.rst

once
-----------------------------------------------------
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_once.rst

restart
-----------------------------------------------------
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_restart.rst

service-list
-----------------------------------------------------
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_service_list.rst

start
-----------------------------------------------------
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_start.rst

status
-----------------------------------------------------
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_status.rst

High Availability
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_status_ha.rst

Log Files
+++++++++++++++++++++++++++++++++++++++++++++++++++++
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_status_logs.rst

stop
-----------------------------------------------------
.. warning:: .. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_stop_ubuntu12.rst

.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_stop.rst

tail
-----------------------------------------------------
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_tail.rst

term
-----------------------------------------------------
.. include:: ../../includes_ctl_private_chef/includes_ctl_private_chef_term.rst

