Twitter's Bootstrap-based PHPBB3 Theme
======================================

This project's goal is to create a base theme for phpbb3, that is based on Twitter Bootstrap and FontAwesome icons.

Currently, this project is based on **phpBB 3.0.11**

Note: This project is not release-ready yet. It's still in development!


Usage Instructions
------------------

1. Install phpBB 3.0.11 [http://www.phpbb.com].
2. Copy `/styles/phpbbstrap` into your phpBB's `/styles/` directory.
3. Modify files below to make sure all the required extra support variables are present (or if you are using a stock setup without any MODs, you can just overwrite them with the ones included here!).

Modifications Required on core PHPBB Files
------------------------------------------

**index.php**
_(around line 133) add:_

	'CURRENT_USERNAME'	=> $user->data['username'],

