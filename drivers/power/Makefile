# SPDX-License-Identifier: GPL-2.0-only
obj-$(CONFIG_POWER_AVS)		+= avs/
obj-$(CONFIG_POWER_RESET)	+= reset/
obj-$(CONFIG_POWER_SUPPLY)	+= supply/
#ifdef OPLUS_FEATURE_CHG_BASIC
ifeq ($(strip $(CONFIG_OPLUS_CHG_OP9RT_PMIC_VOOCPHY)), y)
	obj-$(CONFIG_OPLUS_SM8350_CHARGER)	+= oplus/
else
	obj-$(CONFIG_OPLUS_SM8350_CHARGER)	+= oplus_chg/
endif
#endif
