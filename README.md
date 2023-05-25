# Aspose-Cells-23.4-cracked-jar

First add in your Java project or maven dependency.
Before using their method we have to authorized first. So, below code is used to authorized with the jar.

        try {
            InputStream is = com.aspose.cells.License.class.getResourceAsStream("/com.aspose.cells.lic_2999.xml");
            License asposeLicense = new License();
            asposeLicense.setLicense(is);
            System.out.println(License.getSubscriptionExpireDate());
            is.close();
            result = true;
        } catch (Exception e) {
            e.printStackTrace();
        }
