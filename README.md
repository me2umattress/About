<?php
$theme=wp_get_theme('boutique');$boutique_version	= $theme['Version'];
$theme=wp_get_theme('storefront');$storefront_version	= $theme['Version'];

require_once('inc/class-boutique.php');require_once('inc/class-boutique-customizer.php');
require_once('inc/class-boutique-template.php');require_once( 'inc/class-boutique-integrations.php' );



