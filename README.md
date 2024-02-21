# EdCast Xliff Widgets

The Edcast translator framework converts the YAML file to XLIFF and the XLIFF files are sent to the translation vendor. Once the translated files are recieved in XLIFF, it then gets converted to JSON file to be deployed to the actual environment. 

In some cases, the XLIFF file needs to be modified to make the customer specific changes or vendor overridden strings to be modified directly in the XLIFF files. The vendor will ignore these strings tagged as custom or not required to be translated.

# Freeze

During the translation cut-off period, a temporary freeze will be required to be implemented, preventing any modifications to the XLIFF files. This precautionary measure will be put in place to safeguard the integrity of the translated strings and avoid unintentional overwrites or disruptions to the translated output.
