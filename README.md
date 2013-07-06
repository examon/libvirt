More intelligent virsh auto-completion
======================================

Even though there's already some auto-completion in virsh, it is not enough.
For better user experience, virsh should auto complete objects to virsh commands,
e.g. "start " lists not only options that the start command knows, but list of
inactive domains as well. Moreover, the same applies to command options.
