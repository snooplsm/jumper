BUILD:

	mvn install source:jar


USAGE:

	JumpDialog d = new JumpDialog(this,new JumpListener() {

		@Override
		public void onJump(Character c) {

		}

	});

	d.show();

GOTCHAS:

It supports landscape and portrait but it is up to the user to maintain the changes.  We will provide an activity soon.

