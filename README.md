XML-Sitemap for OXID
=========

Installation

	1. download this package, extract it and upload it to the doc root of your shop installation 
	2. open the file with a text editor or your IDE and enter your details for URL and database
	3. fire up your browser at [http://www.youroxideshop.com/google_sitemap_xml.php] to generate a new sitemap file

Configuration

    // configuration data
    $mod_cnf['filepath']            = './';						// fullpath to sitemaps
    $mod_cnf['filename']            = 'sitemap';				// basename for sitemaps
    $mod_cnf['offset']              = 20000;					// how many product-urls in each sitemap? (max. allowed: 50.000 urls (total, with cats and cms) && max. filesize: 10Mb (uncompressed!))         
    $mod_cnf['language']            = 0;                        // shop language id
    $mod_cnf['expired']             = true;                     // true for using also oxseo.oxexpired = 1 (normally only oxseo.oxexpired = 0)

    // configuration export
    $mod_cnf['export_categories']   = true;                     // export categories?
    $mod_cnf['export_products']     = true;                     // export products?
    $mod_cnf['export_products_ma']  = true;                     // export manufacturer products?
    $mod_cnf['export_products_ve']  = true;                     // export vendor products?
    $mod_cnf['export_cms']          = true;                     // export cms pages?
    $mod_cnf['export_vendor']       = true;                     // export vendors?
    $mod_cnf['export_manufcaturer'] = true;                     // export manufacturers?
    $mod_cnf['export_tags']         = true;                     // export tags?
    $mod_cnf['export_static']       = true;                     // export static seo urls?


License

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
    
    
Copyright

	* by DIATOM Internet & Medien GmbH // 27.07.2009
	* by Proud Sourcing GmbH // 19.07.2013


Credentials
	
	Thanks to OXID forum users DIATOM for the basic script and to nullzehn, Piengie and uppaffrath for their modifications.
	This is the path to the appropriate thread at OXID Community forums: http://www.oxid-esales.com/forum/showthread.php?t=1933