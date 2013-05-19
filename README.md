Twitter's Bootstrap-based PHPBB3 Theme
======================================

This project's goal is to create a base theme for phpbb3, that is based on Twitter Bootstrap and FontAwesome icons.


Note: This project is not release-ready yet. It's still in development!


Modifications Required on core PHPBB Files
------------------------------------------

**index.php**
_(around line 133) add:_

	'CURRENT_USERNAME'	=> $user->data['username'],

