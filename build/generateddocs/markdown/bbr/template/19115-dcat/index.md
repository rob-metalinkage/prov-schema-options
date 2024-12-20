
# 19115 XSL test (Schema)

`ogc.bbr.template.19115-dcat` *v0.1*

A sample building block to test XSLT for 19115

[*Status*](http://www.opengis.net/def/status): Under development

## Examples

### ANZ Metlite template for 19115 XML record.
#### xml
```xml
<?xml version="1.0" encoding="UTF-8"?>
<mdb:MD_Metadata xmlns:mdb="http://standards.iso.org/iso/19115/-3/mdb/2.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:cat="http://standards.iso.org/iso/19115/-3/cat/1.0" xmlns:gfc="http://standards.iso.org/iso/19110/gfc/1.1" xmlns:cit="http://standards.iso.org/iso/19115/-3/cit/2.0" xmlns:gcx="http://standards.iso.org/iso/19115/-3/gcx/1.0" xmlns:gex="http://standards.iso.org/iso/19115/-3/gex/1.0" xmlns:lan="http://standards.iso.org/iso/19115/-3/lan/1.0" xmlns:srv="http://standards.iso.org/iso/19115/-3/srv/2.1" xmlns:mas="http://standards.iso.org/iso/19115/-3/mas/1.0" xmlns:mcc="http://standards.iso.org/iso/19115/-3/mcc/1.0" xmlns:mco="http://standards.iso.org/iso/19115/-3/mco/1.0" xmlns:mda="http://standards.iso.org/iso/19115/-3/mda/1.0" xmlns:mds="http://standards.iso.org/iso/19115/-3/mds/2.0" xmlns:mdt="http://standards.iso.org/iso/19115/-3/mdt/2.0" xmlns:mex="http://standards.iso.org/iso/19115/-3/mex/1.0" xmlns:mmi="http://standards.iso.org/iso/19115/-3/mmi/1.0" xmlns:mpc="http://standards.iso.org/iso/19115/-3/mpc/1.0" xmlns:mrc="http://standards.iso.org/iso/19115/-3/mrc/2.0" xmlns:mrd="http://standards.iso.org/iso/19115/-3/mrd/1.0" xmlns:mri="http://standards.iso.org/iso/19115/-3/mri/1.0" xmlns:mrl="http://standards.iso.org/iso/19115/-3/mrl/2.0" xmlns:mrs="http://standards.iso.org/iso/19115/-3/mrs/1.0" xmlns:msr="http://standards.iso.org/iso/19115/-3/msr/2.0" xmlns:mdq="http://standards.iso.org/iso/19157/-2/mdq/1.0" xmlns:mac="http://standards.iso.org/iso/19115/-3/mac/2.0" xmlns:gco="http://standards.iso.org/iso/19115/-3/gco/1.0" xmlns:gml="http://www.opengis.net/gml/3.2" xmlns:xlink="http://www.w3.org/1999/xlink" xsi:schemaLocation="http://standards.iso.org/iso/19115/-3/mdb/2.0 https://schemas.isotc211.org/19115/-3/mdb/2.0/mdb.xsd">
  <mdb:metadataIdentifier>
    <mcc:MD_Identifier>
      <mcc:code>
        <gco:CharacterString>772c5411-7647-4c65-a4b2-acab226385b6</gco:CharacterString>
      </mcc:code>
      <mcc:codeSpace>
        <gco:CharacterString>urn:uuid</gco:CharacterString>
      </mcc:codeSpace>
    </mcc:MD_Identifier>
  </mdb:metadataIdentifier>
  <mdb:defaultLocale>
    <lan:PT_Locale id="EN">
      <lan:language>
        <lan:LanguageCode codeList="http://www.loc.gov/standards/iso639-2/" codeListValue="eng" />
      </lan:language>
      <lan:characterEncoding>
        <lan:MD_CharacterSetCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#MD_CharacterSetCode" codeListValue="anyValidURI" />
      </lan:characterEncoding>
    </lan:PT_Locale>
  </mdb:defaultLocale>
  <mdb:metadataScope>
    <mdb:MD_MetadataScope>
      <mdb:resourceScope>
        <mcc:MD_ScopeCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#MD_ScopeCode" codeListValue="dataset" />
      </mdb:resourceScope>
      <mdb:name gco:nilReason="missing">
        <gco:CharacterString />
      </mdb:name>
    </mdb:MD_MetadataScope>
  </mdb:metadataScope>
  <mdb:contact>
    <cit:CI_Responsibility>
      <cit:role>
        <cit:CI_RoleCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_RoleCode" codeListValue="pointOfContact" />
      </cit:role>
      <cit:party>
        <cit:CI_Organisation>
          <cit:name>
            <gco:CharacterString>...blank organisation contact entry</gco:CharacterString>
          </cit:name>
          <cit:contactInfo>
            <cit:CI_Contact>
              <cit:address>
                <cit:CI_Address>
                  <cit:electronicMailAddress>
                    <gco:CharacterString>!Manual entry</gco:CharacterString>
                  </cit:electronicMailAddress>
                </cit:CI_Address>
              </cit:address>
            </cit:CI_Contact>
          </cit:contactInfo>
          <cit:individual>
            <cit:CI_Individual>
              <cit:name>
                <gco:CharacterString>!Manual entry</gco:CharacterString>
              </cit:name>
            </cit:CI_Individual>
          </cit:individual>
        </cit:CI_Organisation>
      </cit:party>
    </cit:CI_Responsibility>
  </mdb:contact>
  <mdb:dateInfo>
    <cit:CI_Date>
      <cit:date>
        <gco:DateTime>2024-12-08T23:35:08.125Z</gco:DateTime>
      </cit:date>
      <cit:dateType>
        <cit:CI_DateTypeCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_DateTypeCode" codeListValue="creation" />
      </cit:dateType>
    </cit:CI_Date>
  </mdb:dateInfo>
  <mdb:dateInfo>
    <cit:CI_Date>
      <cit:date>
        <gco:DateTime>2024-12-10T03:02:07.895Z</gco:DateTime>
      </cit:date>
      <cit:dateType>
        <cit:CI_DateTypeCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_DateTypeCode" codeListValue="revision" />
      </cit:dateType>
    </cit:CI_Date>
  </mdb:dateInfo>
  <mdb:dateInfo>
    <cit:CI_Date>
      <cit:date>
        <gco:DateTime>2021-06-18T11:13:24</gco:DateTime>
      </cit:date>
      <cit:dateType>
        <cit:CI_DateTypeCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_DateTypeCode" codeListValue="creation" />
      </cit:dateType>
    </cit:CI_Date>
  </mdb:dateInfo>
  <mdb:metadataStandard>
    <cit:CI_Citation>
      <cit:title>
        <gco:CharacterString>ISO 19115-1:2018-ICSM</gco:CharacterString>
      </cit:title>
      <cit:edition>
        <gco:CharacterString>2018</gco:CharacterString>
      </cit:edition>
    </cit:CI_Citation>
  </mdb:metadataStandard>
  <mdb:metadataLinkage>
    <cit:CI_OnlineResource>
      <cit:linkage>
        <gco:CharacterString>https://atlas.metadata.ga.gov.au:80/geonetwork/srv/api/records/772c5411-7647-4c65-a4b2-acab226385b6</gco:CharacterString>
      </cit:linkage>
      <cit:function>
        <cit:CI_OnLineFunctionCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_OnLineFunctionCode" codeListValue="completeMetadata" />
      </cit:function>
    </cit:CI_OnlineResource>
  </mdb:metadataLinkage>
  <mdb:referenceSystemInfo>
    <mrs:MD_ReferenceSystem>
      <mrs:referenceSystemIdentifier>
        <mcc:MD_Identifier>
          <mcc:code>
            <gco:CharacterString>xxxx.xx (decimal year)</gco:CharacterString>
          </mcc:code>
          <mcc:description>
            <gco:CharacterString>Coordinate epoch</gco:CharacterString>
          </mcc:description>
        </mcc:MD_Identifier>
      </mrs:referenceSystemIdentifier>
      <mrs:referenceSystemType>
        <mrs:MD_ReferenceSystemTypeCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#MD_ReferenceSystemTypeCode" codeListValue="temporal" />
      </mrs:referenceSystemType>
    </mrs:MD_ReferenceSystem>
  </mdb:referenceSystemInfo>
  <mdb:identificationInfo>
    <mri:MD_DataIdentification>
      <mri:citation>
        <cit:CI_Citation>
          <cit:title>
            <gco:CharacterString>Copy of template ANZMet Lite Dataset Template created at 2024-12-09T10:35:08.124+11:00[Australia/Sydney]</gco:CharacterString>
          </cit:title>
          <cit:date>
            <cit:CI_Date>
              <cit:date>
                <gco:DateTime>2023-09-21T08:13:04+00:00</gco:DateTime>
              </cit:date>
              <cit:dateType>
                <cit:CI_DateTypeCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_DateTypeCode" codeListValue="creation" />
              </cit:dateType>
            </cit:CI_Date>
          </cit:date>
          <cit:date>
            <cit:CI_Date>
              <cit:date>
                <gco:DateTime>2023-09-21T08:13:06+00:00</gco:DateTime>
              </cit:date>
              <cit:dateType>
                <cit:CI_DateTypeCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_DateTypeCode" codeListValue="publication" />
              </cit:dateType>
            </cit:CI_Date>
          </cit:date>
          <cit:identifier />
          <cit:identifier>
            <mcc:MD_Identifier>
              <mcc:code gco:nilReason="missing">
                <gco:CharacterString />
              </mcc:code>
              <mcc:description gco:nilReason="missing">
                <gco:CharacterString />
              </mcc:description>
            </mcc:MD_Identifier>
          </cit:identifier>
          <cit:citedResponsibleParty>
            <cit:CI_Responsibility>
              <cit:role>
                <cit:CI_RoleCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_RoleCode" codeListValue="author" />
              </cit:role>
              <cit:party>
                <cit:CI_Organisation>
                  <cit:name>
                    <gco:CharacterString>Org Name</gco:CharacterString>
                  </cit:name>
                  <cit:contactInfo>
                    <cit:CI_Contact>
                      <cit:address>
                        <cit:CI_Address>
                          <cit:electronicMailAddress>
                            <gco:CharacterString>email@addre.ss</gco:CharacterString>
                          </cit:electronicMailAddress>
                        </cit:CI_Address>
                      </cit:address>
                    </cit:CI_Contact>
                  </cit:contactInfo>
                </cit:CI_Organisation>
              </cit:party>
            </cit:CI_Responsibility>
          </cit:citedResponsibleParty>
          <cit:presentationForm>
            <cit:CI_PresentationFormCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_PresentationFormCode" codeListValue="" />
          </cit:presentationForm>
        </cit:CI_Citation>
      </mri:citation>
      <mri:abstract>
        <gco:CharacterString>Information about the dataset</gco:CharacterString>
      </mri:abstract>
      <mri:purpose gco:nilReason="missing">
        <gco:CharacterString />
      </mri:purpose>
      <mri:status>
        <mcc:MD_ProgressCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#MD_ProgressCode" codeListValue="" />
      </mri:status>
      <mri:pointOfContact>
        <cit:CI_Responsibility>
          <cit:role>
            <cit:CI_RoleCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_RoleCode" codeListValue="pointOfContact" />
          </cit:role>
          <cit:party>
            <cit:CI_Organisation>
              <cit:name>
                <gco:CharacterString>Org Name</gco:CharacterString>
              </cit:name>
              <cit:contactInfo>
                <cit:CI_Contact>
                  <cit:address>
                    <cit:CI_Address>
                      <cit:electronicMailAddress>
                        <gco:CharacterString>email@addre.ss</gco:CharacterString>
                      </cit:electronicMailAddress>
                    </cit:CI_Address>
                  </cit:address>
                </cit:CI_Contact>
              </cit:contactInfo>
            </cit:CI_Organisation>
          </cit:party>
        </cit:CI_Responsibility>
      </mri:pointOfContact>
      <mri:pointOfContact>
        <cit:CI_Responsibility>
          <cit:role>
            <cit:CI_RoleCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_RoleCode" codeListValue="publisher" />
          </cit:role>
          <cit:party>
            <cit:CI_Organisation>
              <cit:name>
                <gco:CharacterString>Org Name</gco:CharacterString>
              </cit:name>
              <cit:contactInfo>
                <cit:CI_Contact>
                  <cit:address>
                    <cit:CI_Address>
                      <cit:electronicMailAddress>
                        <gco:CharacterString>email@addre.ss</gco:CharacterString>
                      </cit:electronicMailAddress>
                    </cit:CI_Address>
                  </cit:address>
                </cit:CI_Contact>
              </cit:contactInfo>
            </cit:CI_Organisation>
          </cit:party>
        </cit:CI_Responsibility>
      </mri:pointOfContact>
      <mri:spatialRepresentationType>
        <mcc:MD_SpatialRepresentationTypeCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#MD_SpatialRepresentationTypeCode" codeListValue="" />
      </mri:spatialRepresentationType>
      <mri:spatialResolution>
        <mri:MD_Resolution>
          <mri:equivalentScale>
            <mri:MD_RepresentativeFraction>
              <mri:denominator>
                <gco:Integer>50000</gco:Integer>
              </mri:denominator>
            </mri:MD_RepresentativeFraction>
          </mri:equivalentScale>
        </mri:MD_Resolution>
      </mri:spatialResolution>
      <mri:topicCategory>
        <mri:MD_TopicCategoryCode>environment</mri:MD_TopicCategoryCode>
      </mri:topicCategory>
      <mri:extent>
        <gex:EX_Extent>
          <gex:geographicElement>
            <gex:EX_GeographicBoundingBox>
              <gex:westBoundLongitude>
                <gco:Decimal>112.92</gco:Decimal>
              </gex:westBoundLongitude>
              <gex:eastBoundLongitude>
                <gco:Decimal>159.11</gco:Decimal>
              </gex:eastBoundLongitude>
              <gex:southBoundLatitude>
                <gco:Decimal>-54.75</gco:Decimal>
              </gex:southBoundLatitude>
              <gex:northBoundLatitude>
                <gco:Decimal>-9.2402</gco:Decimal>
              </gex:northBoundLatitude>
            </gex:EX_GeographicBoundingBox>
          </gex:geographicElement>
        </gex:EX_Extent>
      </mri:extent>
      <mri:resourceMaintenance>
        <mmi:MD_MaintenanceInformation>
          <mmi:maintenanceAndUpdateFrequency>
            <mmi:MD_MaintenanceFrequencyCode codeListValue="asNeeded" codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#MD_MaintenanceFrequencyCode" />
          </mmi:maintenanceAndUpdateFrequency>
          <mmi:maintenanceDate>
            <cit:CI_Date>
              <cit:date>
                <gco:DateTime>2023-09-21T08:13:07+00:00</gco:DateTime>
              </cit:date>
              <cit:dateType>
                <cit:CI_DateTypeCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_DateTypeCode" codeListValue="lastUpdate" />
              </cit:dateType>
            </cit:CI_Date>
          </mmi:maintenanceDate>
          <mmi:maintenanceNote>
            <gco:CharacterString>Commit message</gco:CharacterString>
          </mmi:maintenanceNote>
        </mmi:MD_MaintenanceInformation>
      </mri:resourceMaintenance>
      <mri:graphicOverview>
        <mcc:MD_BrowseGraphic>
          <mcc:fileName>
            <gco:CharacterString>Filename for thumbnail image for the dataset</gco:CharacterString>
          </mcc:fileName>
          <mcc:linkage>
            <cit:CI_OnlineResource>
              <cit:linkage>
                <gco:CharacterString>(Linkage to Browse graphic)</gco:CharacterString>
              </cit:linkage>
              <cit:protocol gco:nilReason="missing">
                <gco:CharacterString />
              </cit:protocol>
              <cit:name gco:nilReason="missing">
                <gco:CharacterString />
              </cit:name>
              <cit:description gco:nilReason="missing">
                <gco:CharacterString />
              </cit:description>
              <cit:function>
                <cit:CI_OnLineFunctionCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_OnLineFunctionCode" codeListValue="" />
              </cit:function>
            </cit:CI_OnlineResource>
          </mcc:linkage>
        </mcc:MD_BrowseGraphic>
      </mri:graphicOverview>
      <mri:descriptiveKeywords>
        <mri:MD_Keywords>
          <mri:keyword gco:nilReason="missing">
            <gco:CharacterString />
          </mri:keyword>
          <mri:type>
            <mri:MD_KeywordTypeCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#MD_KeywordTypeCode" codeListValue="place" />
          </mri:type>
          <mri:thesaurusName>
            <cit:CI_Citation>
              <cit:title>
                <gcx:Anchor xlink:href="http://geonetwork-opensource.org/thesaurus/naturalearth-and-seavox">Continents, countries, sea regions of the world.</gcx:Anchor>
              </cit:title>
              <cit:date>
                <cit:CI_Date>
                  <cit:date>
                    <gco:Date>2015-01-01</gco:Date>
                  </cit:date>
                  <cit:dateType>
                    <cit:CI_DateTypeCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_DateTypeCode" codeListValue="publication" />
                  </cit:dateType>
                </cit:CI_Date>
              </cit:date>
              <cit:date>
                <cit:CI_Date>
                  <cit:date>
                    <gco:Date>2015-07-17</gco:Date>
                  </cit:date>
                  <cit:dateType>
                    <cit:CI_DateTypeCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_DateTypeCode" codeListValue="publication" />
                  </cit:dateType>
                </cit:CI_Date>
              </cit:date>
              <cit:identifier>
                <mcc:MD_Identifier>
                  <mcc:code>
                    <gcx:Anchor xlink:href="https://atlas.metadata.ga.gov.au/geonetwork/srv/api/registries/vocabularies/external.place.regions">geonetwork.thesaurus.external.place.regions</gcx:Anchor>
                  </mcc:code>
                </mcc:MD_Identifier>
              </cit:identifier>
            </cit:CI_Citation>
          </mri:thesaurusName>
        </mri:MD_Keywords>
      </mri:descriptiveKeywords>
      <mri:resourceConstraints>
        <mco:MD_Constraints>
          <mco:useLimitation gco:nilReason="missing">
            <gco:CharacterString />
          </mco:useLimitation>
        </mco:MD_Constraints>
      </mri:resourceConstraints>
      <mri:defaultLocale>
        <lan:PT_Locale>
          <lan:language>
            <lan:LanguageCode codeList="http://www.loc.gov/standards/iso639-2/" codeListValue="eng" />
          </lan:language>
          <lan:characterEncoding>
            <lan:MD_CharacterSetCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#MD_CharacterSetCode" codeListValue="utf8" />
          </lan:characterEncoding>
        </lan:PT_Locale>
      </mri:defaultLocale>
      <mri:supplementalInformation>
        <gco:CharacterString>Any additional comments about this dataset</gco:CharacterString>
      </mri:supplementalInformation>
    </mri:MD_DataIdentification>
  </mdb:identificationInfo>
  <mdb:distributionInfo>
    <mrd:MD_Distribution>
      <mrd:transferOptions>
        <mrd:MD_DigitalTransferOptions>
          <mrd:onLine>
            <cit:CI_OnlineResource>
              <cit:linkage>
                <gco:CharacterString>Distro URL</gco:CharacterString>
              </cit:linkage>
              <cit:protocol gco:nilReason="missing">
                <gco:CharacterString />
              </cit:protocol>
              <cit:name>
                <gco:CharacterString>Name of resource</gco:CharacterString>
              </cit:name>
              <cit:description gco:nilReason="missing">
                <gco:CharacterString />
              </cit:description>
              <cit:function>
                <cit:CI_OnLineFunctionCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_OnLineFunctionCode" codeListValue="download" />
              </cit:function>
            </cit:CI_OnlineResource>
          </mrd:onLine>
        </mrd:MD_DigitalTransferOptions>
      </mrd:transferOptions>
    </mrd:MD_Distribution>
  </mdb:distributionInfo>
  <mdb:resourceLineage>
    <mrl:LI_Lineage>
      <mrl:statement>
        <gco:CharacterString>Information that lets the user understand how the dataset was created over time.</gco:CharacterString>
      </mrl:statement>
      <mrl:source>
        <mrl:LI_Source>
          <mrl:description>
            <gco:CharacterString>Describe the Information Sources that went into building this dataset</gco:CharacterString>
          </mrl:description>
        </mrl:LI_Source>
      </mrl:source>
    </mrl:LI_Lineage>
  </mdb:resourceLineage>
  <mdb:metadataConstraints>
    <mco:MD_LegalConstraints>
      <mco:useLimitation>
        <gco:CharacterString>CC BY-SA</gco:CharacterString>
      </mco:useLimitation>
      <mco:constraintApplicationScope>
        <mcc:MD_Scope>
          <mcc:level>
            <mcc:MD_ScopeCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#MD_ScopeCode" codeListValue="document" />
          </mcc:level>
        </mcc:MD_Scope>
      </mco:constraintApplicationScope>
      <mco:reference>
        <cit:CI_Citation>
          <cit:title>
            <gco:CharacterString>Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)</gco:CharacterString>
          </cit:title>
          <cit:onlineResource>
            <cit:CI_OnlineResource>
              <cit:linkage>
                <gco:CharacterString>https://creativecommons.org/licenses/by-sa/4.0/</gco:CharacterString>
              </cit:linkage>
              <cit:protocol>
                <gco:CharacterString>https</gco:CharacterString>
              </cit:protocol>
              <cit:name>
                <gco:CharacterString>Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)</gco:CharacterString>
              </cit:name>
              <cit:description>
                <gco:CharacterString>Human readable summary of CC BY-SA</gco:CharacterString>
              </cit:description>
              <cit:function>
                <cit:CI_OnLineFunctionCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_OnLineFunctionCode" codeListValue="" />
              </cit:function>
            </cit:CI_OnlineResource>
          </cit:onlineResource>
        </cit:CI_Citation>
      </mco:reference>
      <mco:releasability>
        <mco:MD_Releasability>
          <mco:addressee />
          <mco:statement>
            <gco:CharacterString>Creative Commons Attribution ShareAlike 4</gco:CharacterString>
          </mco:statement>
          <mco:disseminationConstraints>
            <mco:MD_RestrictionCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#MD_RestrictionCode" codeListValue="license" />
          </mco:disseminationConstraints>
        </mco:MD_Releasability>
      </mco:releasability>
      <mco:accessConstraints>
        <mco:MD_RestrictionCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#MD_RestrictionCode" codeListValue="copyright" />
      </mco:accessConstraints>
      <mco:useConstraints>
        <mco:MD_RestrictionCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#MD_RestrictionCode" codeListValue="" />
      </mco:useConstraints>
    </mco:MD_LegalConstraints>
  </mdb:metadataConstraints>
  <mdb:metadataConstraints>
    <mco:MD_SecurityConstraints>
      <mco:useLimitation>
        <gco:CharacterString>UNOFFICIAL</gco:CharacterString>
      </mco:useLimitation>
      <mco:reference>
        <cit:CI_Citation>
          <cit:title>
            <gco:CharacterString>Protective Security Australia - UNOFFICIAL</gco:CharacterString>
          </cit:title>
          <cit:onlineResource>
            <cit:CI_OnlineResource>
              <cit:linkage>
                <gco:CharacterString>https://www.protectivesecurity.gov.au/information/sensitive-classified-information/Pages/default.aspx</gco:CharacterString>
              </cit:linkage>
              <cit:protocol>
                <gco:CharacterString>https</gco:CharacterString>
              </cit:protocol>
              <cit:name gco:nilReason="missing">
                <gco:CharacterString />
              </cit:name>
              <cit:description gco:nilReason="missing">
                <gco:CharacterString />
              </cit:description>
              <cit:function>
                <cit:CI_OnLineFunctionCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#CI_OnLineFunctionCode" codeListValue="" />
              </cit:function>
            </cit:CI_OnlineResource>
          </cit:onlineResource>
        </cit:CI_Citation>
      </mco:reference>
      <mco:classification>
        <mco:MD_ClassificationCode codeList="http://standards.iso.org/iso/19115/resources/Codelists/cat/codelists.xml#MD_ClassificationCode" codeListValue="unclassified" />
      </mco:classification>
      <mco:userNote>
        <gco:CharacterString>No damage if compromised. Does not form part of official duty.</gco:CharacterString>
      </mco:userNote>
      <mco:classificationSystem>
        <gco:CharacterString>Protective Security Australia</gco:CharacterString>
      </mco:classificationSystem>
    </mco:MD_SecurityConstraints>
  </mdb:metadataConstraints>
</mdb:MD_Metadata>


```


# For developers

The source code for this Building Block can be found in the following repository:

* URL: [https://github.com/rob-metalinkage/prov-schema-options](https://github.com/rob-metalinkage/prov-schema-options)
* Path: `_sources/19115-dcat`

