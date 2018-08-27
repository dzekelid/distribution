---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Contentdistribution Genericdistributionprover Action
    Add
  description: Add new Generic Distribution Provider
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/attuversedistribution_attuverse/action/getFeed:
    get:
      summary: Get Service Attuversedistribution Attuverse Action Getfeed
      description: ""
      operationId: attUverse.getFeed
      x-api-path-slug: serviceattuversedistribution-attuverseactiongetfeed-get
      parameters:
      - in: query
        name: distributionProfileId
      - in: query
        name: hash
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Attuversedistribution
      - Attuverse
      - Action
      - GetFeed
  /service/avndistribution_avn/action/getFeed:
    get:
      summary: Get Service Avndistribution Avn Action Getfeed
      description: ""
      operationId: avn.getFeed
      x-api-path-slug: serviceavndistribution-avnactiongetfeed-get
      parameters:
      - in: query
        name: distributionProfileId
      - in: query
        name: hash
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Avndistribution
      - Avn
      - Action
      - GetFeed
  /service/comcastmrssdistribution_comcastmrss/action/getFeed:
    get:
      summary: Get Service Comcastmrssdistribution Comcastmrss Action Getfeed
      description: ""
      operationId: comcastMrss.getFeed
      x-api-path-slug: servicecomcastmrssdistribution-comcastmrssactiongetfeed-get
      parameters:
      - in: query
        name: distributionProfileId
      - in: query
        name: hash
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Comcastmrssdistribution
      - Comcastmrss
      - Action
      - GetFeed
  /service/contentdistribution_contentdistributionbatch/action/createRequiredJobs:
    get:
      summary: Get Service Contentdistribution Contentdistributionbatch Action Createrequiredjobs
      description: creates all required jobs according to entry distribution dirty
        flags
      operationId: contentDistributionBatch.createRequiredJobs
      x-api-path-slug: servicecontentdistribution-contentdistributionbatchactioncreaterequiredjobs-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Contentdistributionbatch
      - Action
      - CreateRequiredJobs
  /service/contentdistribution_contentdistributionbatch/action/getAssetUrl:
    get:
      summary: Get Service Contentdistribution Contentdistributionbatch Action Getasseturl
      description: returns absolute valid url for asset file
      operationId: contentDistributionBatch.getAssetUrl
      x-api-path-slug: servicecontentdistribution-contentdistributionbatchactiongetasseturl-get
      parameters:
      - in: query
        name: assetId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Contentdistributionbatch
      - Action
      - GetAssetUrl
  /service/contentdistribution_contentdistributionbatch/action/updateSunStatus:
    get:
      summary: Get Service Contentdistribution Contentdistributionbatch Action Updatesunstatus
      description: updates entry distribution sun status in the search engine
      operationId: contentDistributionBatch.updateSunStatus
      x-api-path-slug: servicecontentdistribution-contentdistributionbatchactionupdatesunstatus-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Contentdistributionbatch
      - Action
      - UpdateSunStatus
  /service/contentdistribution_distributionprofile/action/add:
    get:
      summary: Get Service Contentdistribution Distributionprofile Action Add
      description: Add new Distribution Profile
      operationId: distributionProfile.add
      x-api-path-slug: servicecontentdistribution-distributionprofileactionadd-get
      parameters:
      - in: query
        name: distributionProfile[accountId]
      - in: query
        name: distributionProfile[adFreeApplicationGuid]
        description: The GUID for the application in which to record metrics and enforce
          business rules obtained through your Unicorn representative
      - in: query
        name: distributionProfile[adServerPartnerId]
      - in: query
        name: distributionProfile[allowAdsenseForVideo]
      - in: query
        name: distributionProfile[allowComments]
      - in: query
        name: distributionProfile[allowDownload]
      - in: query
        name: distributionProfile[allowEmbedding]
      - in: query
        name: distributionProfile[allowInvideo]
      - in: query
        name: distributionProfile[allowMidRollAds]
      - in: query
        name: distributionProfile[allowPostRollAds]
      - in: query
        name: distributionProfile[allowPreRollAds]
      - in: query
        name: distributionProfile[allowRatings]
      - in: query
        name: distributionProfile[allowResponses]
      - in: query
        name: distributionProfile[allowStreaming]
      - in: query
        name: distributionProfile[allowSyndication]
      - in: query
        name: distributionProfile[apiAuthorizeUrl]
      - in: query
        name: distributionProfile[apiHostUrl]
        description: The API host URL that the Upload User should have access to,
          Used for HTTP content submission
      - in: query
        name: distributionProfile[apikey]
      - in: query
        name: distributionProfile[asperaHost]
      - in: query
        name: distributionProfile[asperaLogin]
      - in: query
        name: distributionProfile[asperaPass]
      - in: query
        name: distributionProfile[asperaPrivateKey]
      - in: query
        name: distributionProfile[asperaPublicKey]
      - in: query
        name: distributionProfile[assetFilenameXslt]
      - in: query
        name: distributionProfile[assumeSuccess]
      - in: query
        name: distributionProfile[autoCreateFlavors]
        description: Comma separated flavor params ids that should be auto converted
      - in: query
        name: distributionProfile[autoCreateThumb]
        description: Comma separated thumbnail params ids that should be auto generated
      - in: query
        name: distributionProfile[backgroundImageStandard]
      - in: query
        name: distributionProfile[backgroundImageWide]
      - in: query
        name: distributionProfile[basePath]
      - in: query
        name: distributionProfile[blockOutsideOwnership]
      - in: query
        name: distributionProfile[bodyXslt]
      - in: query
        name: distributionProfile[captionAutosync]
      - in: query
        name: distributionProfile[categoryId]
      - in: query
        name: distributionProfile[certificateKey]
      - in: query
        name: distributionProfile[channelCopyright]
      - in: query
        name: distributionProfile[channelDescription]
      - in: query
        name: distributionProfile[channelGenerator]
      - in: query
        name: distributionProfile[channelGuid]
        description: The Channel GUID assigned to this Publication Rule
      - in: query
        name: distributionProfile[channelImageHeight]
      - in: query
        name: distributionProfile[channelImageLink]
      - in: query
        name: distributionProfile[channelImageTitle]
      - in: query
        name: distributionProfile[channelImageUrl]
      - in: query
        name: distributionProfile[channelImageWidth]
      - in: query
        name: distributionProfile[channelLanguage]
      - in: query
        name: distributionProfile[channelLink]
      - in: query
        name: distributionProfile[channelManagingEditor]
      - in: query
        name: distributionProfile[channelRating]
      - in: query
        name: distributionProfile[channelTitle]
      - in: query
        name: distributionProfile[claimType]
      - in: query
        name: distributionProfile[commercialPolicy]
      - in: query
        name: distributionProfile[contactEmail]
      - in: query
        name: distributionProfile[contactTelephone]
      - in: query
        name: distributionProfile[contentOwner]
      - in: query
        name: distributionProfile[copyright]
      - in: query
        name: distributionProfile[cPlatformTvSeriesField]
      - in: query
        name: distributionProfile[cPlatformTvSeries]
      - in: query
        name: distributionProfile[csId]
      - in: query
        name: distributionProfile[cuePointsProvider]
      - in: query
        name: distributionProfile[defaultCategory]
      - in: query
        name: distributionProfile[deleteEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: distributionProfile[deleteReference]
      - in: query
        name: distributionProfile[disableEpisodeNumberCustomValidation]
      - in: query
        name: distributionProfile[disableMetadata]
      - in: query
        name: distributionProfile[distributeCaptions]
      - in: query
        name: distributionProfile[distributeCuePoints]
      - in: query
        name: distributionProfile[distributeRemoteCaptionAssetContent]
      - in: query
        name: distributionProfile[distributeRemoteFlavorAssetContent]
      - in: query
        name: distributionProfile[distributeRemoteThumbAssetContent]
      - in: query
        name: distributionProfile[domainGuid]
        description: The GUID of the Customer Domain in the Unicorn system obtained
          by contacting your Unicorn representative
      - in: query
        name: distributionProfile[domainName]
        description: The name of the Domain that the Upload User should have access
          to, Used for authentication
      - in: query
        name: distributionProfile[domain]
      - in: query
        name: distributionProfile[downloadPriceCode]
      - in: query
        name: distributionProfile[email]
      - in: query
        name: distributionProfile[enableAdServer]
      - in: query
        name: distributionProfile[entitlements]
      - in: query
        name: distributionProfile[entitlement]
      - in: query
        name: distributionProfile[feedAuthorName]
      - in: query
        name: distributionProfile[feedCopyright]
      - in: query
        name: distributionProfile[feedDescription]
      - in: query
        name: distributionProfile[feedImageHeight]
      - in: query
        name: distributionProfile[feedImageLink]
      - in: query
        name: distributionProfile[feedImageTitle]
      - in: query
        name: distributionProfile[feedImageUrl]
      - in: query
        name: distributionProfile[feedImageWidth]
      - in: query
        name: distributionProfile[feedLanguage]
      - in: query
        name: distributionProfile[feedLastBuildDate]
      - in: query
        name: distributionProfile[feedLink]
      - in: query
        name: distributionProfile[feedSpecVersion]
        description: 'Enum Type: `KalturaYouTubeDistributionFeedSpecVersion`'
      - in: query
        name: distributionProfile[feedSubtitle]
      - in: query
        name: distributionProfile[feedTitle]
      - in: query
        name: distributionProfile[fieldConfigArray]
      - in: query
        name: distributionProfile[flavorAssetFilenameXslt]
      - in: query
        name: distributionProfile[flvFlavorParamsId]
      - in: query
        name: distributionProfile[ftpHost]
      - in: query
        name: distributionProfile[ftpLogin]
      - in: query
        name: distributionProfile[ftpPassword]
      - in: query
        name: distributionProfile[ftpPass]
      - in: query
        name: distributionProfile[ftpPath]
      - in: query
        name: distributionProfile[ftpUsername]
      - in: query
        name: distributionProfile[genericProviderId]
        description: '`insertOnly`'
      - in: query
        name: distributionProfile[geoBlockingMapping]
        description: 'Enum Type: `KalturaDailymotionGeoBlockingMapping`'
      - in: query
        name: distributionProfile[googleClientId]
      - in: query
        name: distributionProfile[googleClientSecret]
      - in: query
        name: distributionProfile[googleTokenData]
      - in: query
        name: distributionProfile[hideViewCount]
      - in: query
        name: distributionProfile[host]
      - in: query
        name: distributionProfile[ignoreSchedulingInFeed]
      - in: query
        name: distributionProfile[ingestUrl]
      - in: query
        name: distributionProfile[instreamStandard]
      - in: query
        name: distributionProfile[instreamTrueview]
      - in: query
        name: distributionProfile[ips]
      - in: query
        name: distributionProfile[itemLink]
      - in: query
        name: distributionProfile[itemMediaRating]
      - in: query
        name: distributionProfile[itemsPerPage]
      - in: query
        name: distributionProfile[itemType]
      - in: query
        name: distributionProfile[itemXpathsToExtend]
      - in: query
        name: distributionProfile[mapAccessControlProfileIds]
      - in: query
        name: distributionProfile[mapCaptionParamsIds]
      - in: query
        name: distributionProfile[mapConversionProfileIds]
      - in: query
        name: distributionProfile[mapFlavorParamsIds]
      - in: query
        name: distributionProfile[mapMetadataProfileIds]
      - in: query
        name: distributionProfile[mapStorageProfileIds]
      - in: query
        name: distributionProfile[mapThumbParamsIds]
      - in: query
        name: distributionProfile[metadataFilenameXslt]
      - in: query
        name: distributionProfile[metadataProfileId]
      - in: query
        name: distributionProfile[metadataXpathsTriggerUpdate]
      - in: query
        name: distributionProfile[metadataXslt]
      - in: query
        name: distributionProfile[msnvideoCat]
      - in: query
        name: distributionProfile[msnvideoTopCat]
      - in: query
        name: distributionProfile[msnvideoTop]
      - in: query
        name: distributionProfile[name]
      - in: query
        name: distributionProfile[notificationEmail]
      - in: query
        name: distributionProfile[objectType]
      - in: query
        name: distributionProfile[optionalAssetDistributionRules]
      - in: query
        name: distributionProfile[optionalFlavorParamsIds]
        description: Comma separated flavor params ids that should be submitted if
          ready
      - in: query
        name: distributionProfile[optionalThumbDimensions]
      - in: query
        name: distributionProfile[overrideManualEdits]
      - in: query
        name: distributionProfile[ownerName]
      - in: query
        name: distributionProfile[pageAccessToken]
      - in: query
        name: distributionProfile[pageGroup]
      - in: query
        name: distributionProfile[pageId]
      - in: query
        name: distributionProfile[passphrase]
      - in: query
        name: distributionProfile[password]
      - in: query
        name: distributionProfile[permissions]
      - in: query
        name: distributionProfile[port]
      - in: query
        name: distributionProfile[priority]
      - in: query
        name: distributionProfile[privacyStatus]
      - in: query
        name: distributionProfile[processFeed]
        description: 'Enum Type: `KalturaYahooDistributionProcessFeedActionStatus`'
      - in: query
        name: distributionProfile[protocol]
        description: '`insertOnly`Enum Type: `KalturaDistributionProtocol`'
      - in: query
        name: distributionProfile[providerId]
      - in: query
        name: distributionProfile[providerName]
      - in: query
        name: distributionProfile[providerType]
        description: '`insertOnly`Enum Type: `KalturaDistributionProviderType`'
      - in: query
        name: distributionProfile[rating]
      - in: query
        name: distributionProfile[recommendedDcForDownload]
        description: The best Kaltura data center to be used to download the asset
          files to
      - in: query
        name: distributionProfile[recommendedDcForExecute]
        description: The best Kaltura data center to be used to execute the distribution
          job
      - in: query
        name: distributionProfile[recommendedStorageProfileForDownload]
        description: The best external storage to be used to download the asset files
          from
      - in: query
        name: distributionProfile[releaseClaims]
      - in: query
        name: distributionProfile[remoteAssetParamsId]
        description: The flavor-params that will be used for the remote asset
      - in: query
        name: distributionProfile[replaceAirDates]
      - in: query
        name: distributionProfile[replaceGroup]
      - in: query
        name: distributionProfile[reportEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: distributionProfile[requiredAssetDistributionRules]
      - in: query
        name: distributionProfile[requiredFlavorParamsIds]
        description: Comma separated flavor params ids that required to be ready before
          submission
      - in: query
        name: distributionProfile[requiredThumbDimensions]
      - in: query
        name: distributionProfile[reRequestPermissions]
      - in: query
        name: distributionProfile[seasonNumber]
      - in: query
        name: distributionProfile[seasonSynopsis]
      - in: query
        name: distributionProfile[seasonTuneInInformation]
      - in: query
        name: distributionProfile[sendMetadataAfterAssets]
      - in: query
        name: distributionProfile[seriesAdditionalCategories]
      - in: query
        name: distributionProfile[seriesChannel]
      - in: query
        name: distributionProfile[seriesPrimaryCategory]
      - in: query
        name: distributionProfile[sftpBaseDir]
      - in: query
        name: distributionProfile[sftpBasePath]
      - in: query
        name: distributionProfile[sftpHost]
      - in: query
        name: distributionProfile[sftpLogin]
      - in: query
        name: distributionProfile[sftpPass]
      - in: query
        name: distributionProfile[sftpPort]
      - in: query
        name: distributionProfile[sftpPrivateKey]
      - in: query
        name: distributionProfile[sftpPublicKey]
      - in: query
        name: distributionProfile[shouldAddThumbExtension]
      - in: query
        name: distributionProfile[shouldIncludeCaptions]
      - in: query
        name: distributionProfile[shouldIncludeCuePoints]
      - in: query
        name: distributionProfile[slFlavorParamsId]
      - in: query
        name: distributionProfile[slHdFlavorParamsId]
      - in: query
        name: distributionProfile[sourceFlavorParamsId]
      - in: query
        name: distributionProfile[sourceFriendlyName]
      - in: query
        name: distributionProfile[source]
      - in: query
        name: distributionProfile[state]
      - in: query
        name: distributionProfile[status]
        description: 'Enum Type: `KalturaDistributionProfileStatus`'
      - in: query
        name: distributionProfile[storageProfileId]
        description: The remote storage that should be used for the remote asset
      - in: query
        name: distributionProfile[streamingPriceCode]
      - in: query
        name: distributionProfile[strict]
      - in: query
        name: distributionProfile[submitAction][ftpPassiveMode]
      - in: query
        name: distributionProfile[submitAction][httpFieldName]
      - in: query
        name: distributionProfile[submitAction][httpFileName]
      - in: query
        name: distributionProfile[submitAction][password]
      - in: query
        name: distributionProfile[submitAction][protocol]
        description: 'Enum Type: `KalturaDistributionProtocol`'
      - in: query
        name: distributionProfile[submitAction][serverPath]
      - in: query
        name: distributionProfile[submitAction][serverUrl]
      - in: query
        name: distributionProfile[submitAction][username]
      - in: query
        name: distributionProfile[submitEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: distributionProfile[sunriseDefaultOffset]
        description: If entry distribution sunrise not specified that will be the
          default since entry creation time, in seconds
      - in: query
        name: distributionProfile[sunsetDefaultOffset]
        description: If entry distribution sunset not specified that will be the default
          since entry creation time, in seconds
      - in: query
        name: distributionProfile[tags]
      - in: query
        name: distributionProfile[targetAccountId]
      - in: query
        name: distributionProfile[targetLoginId]
      - in: query
        name: distributionProfile[targetLoginPassword]
      - in: query
        name: distributionProfile[targetServiceUrl]
      - in: query
        name: distributionProfile[target]
      - in: query
        name: distributionProfile[thumbnailAssetFilenameXslt]
      - in: query
        name: distributionProfile[ugcPolicy]
      - in: query
        name: distributionProfile[updateEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: distributionProfile[upstreamNetworkId]
      - in: query
        name: distributionProfile[upstreamNetworkName]
      - in: query
        name: distributionProfile[upstreamVideoId]
      - in: query
        name: distributionProfile[urgentReference]
      - in: query
        name: distributionProfile[useCategoryEntries]
        description: When checking custom XSLT conditions using the fieldConfigArray
          - address only categories associated with the entry via the categoryEntry
          object
      - in: query
        name: distributionProfile[userAccessToken]
      - in: query
        name: distributionProfile[username]
      - in: query
        name: distributionProfile[user]
      - in: query
        name: distributionProfile[videoMediaType]
      - in: query
        name: distributionProfile[wmvFlavorParamsId]
      - in: query
        name: distributionProfile[xsltFile]
      - in: query
        name: distributionProfile[xsl]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Distributionprofile
      - Action
      - Add
  /service/contentdistribution_distributionprofile/action/delete:
    get:
      summary: Get Service Contentdistribution Distributionprofile Action Delete
      description: Delete Distribution Profile by id
      operationId: distributionProfile.delete
      x-api-path-slug: servicecontentdistribution-distributionprofileactiondelete-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Distributionprofile
      - Action
      - Delete
  /service/contentdistribution_distributionprofile/action/get:
    get:
      summary: Get Service Contentdistribution Distributionprofile Action Get
      description: Get Distribution Profile by id
      operationId: distributionProfile.get
      x-api-path-slug: servicecontentdistribution-distributionprofileactionget-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Distributionprofile
      - Action
      - Get
  /service/contentdistribution_distributionprofile/action/list:
    get:
      summary: Get Service Contentdistribution Distributionprofile Action List
      description: List all distribution providers
      operationId: distributionProfile.list
      x-api-path-slug: servicecontentdistribution-distributionprofileactionlist-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[objectType]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaDistributionProfileStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Distributionprofile
      - Action
      - List
  /service/contentdistribution_distributionprofile/action/listByPartner:
    get:
      summary: Get Service Contentdistribution Distributionprofile Action Listbypartner
      description: ""
      operationId: distributionProfile.listByPartner
      x-api-path-slug: servicecontentdistribution-distributionprofileactionlistbypartner-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[groupTypeEq]
        description: 'Enum Type: `KalturaPartnerGroupType`Eq filter for the partners
          group type'
      - in: query
        name: filter[groupTypeIn]
        description: In filter for the partners group type
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[idNotIn]
      - in: query
        name: filter[nameEqual]
      - in: query
        name: filter[nameLike]
      - in: query
        name: filter[nameMultiLikeAnd]
      - in: query
        name: filter[nameMultiLikeOr]
      - in: query
        name: filter[objectType]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[partnerGroupTypeEqual]
        description: 'Enum Type: `KalturaPartnerGroupType`'
      - in: query
        name: filter[partnerNameDescriptionWebsiteAdminNameAdminEmailLike]
      - in: query
        name: filter[partnerPackageEqual]
      - in: query
        name: filter[partnerPackageGreaterThanOrEqual]
      - in: query
        name: filter[partnerPackageIn]
      - in: query
        name: filter[partnerPackageLessThanOrEqual]
      - in: query
        name: filter[partnerPermissionsExist]
        description: Filter for partner permissions- filter contains comma-separated
          string of permission names which the returned partners should have
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaPartnerStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Distributionprofile
      - Action
      - ListByPartner
  /service/contentdistribution_distributionprofile/action/update:
    get:
      summary: Get Service Contentdistribution Distributionprofile Action Update
      description: Update Distribution Profile by id
      operationId: distributionProfile.update
      x-api-path-slug: servicecontentdistribution-distributionprofileactionupdate-get
      parameters:
      - in: query
        name: distributionProfile[accountId]
      - in: query
        name: distributionProfile[adFreeApplicationGuid]
        description: The GUID for the application in which to record metrics and enforce
          business rules obtained through your Unicorn representative
      - in: query
        name: distributionProfile[adServerPartnerId]
      - in: query
        name: distributionProfile[allowAdsenseForVideo]
      - in: query
        name: distributionProfile[allowComments]
      - in: query
        name: distributionProfile[allowDownload]
      - in: query
        name: distributionProfile[allowEmbedding]
      - in: query
        name: distributionProfile[allowInvideo]
      - in: query
        name: distributionProfile[allowMidRollAds]
      - in: query
        name: distributionProfile[allowPostRollAds]
      - in: query
        name: distributionProfile[allowPreRollAds]
      - in: query
        name: distributionProfile[allowRatings]
      - in: query
        name: distributionProfile[allowResponses]
      - in: query
        name: distributionProfile[allowStreaming]
      - in: query
        name: distributionProfile[allowSyndication]
      - in: query
        name: distributionProfile[apiAuthorizeUrl]
      - in: query
        name: distributionProfile[apiHostUrl]
        description: The API host URL that the Upload User should have access to,
          Used for HTTP content submission
      - in: query
        name: distributionProfile[apikey]
      - in: query
        name: distributionProfile[asperaHost]
      - in: query
        name: distributionProfile[asperaLogin]
      - in: query
        name: distributionProfile[asperaPass]
      - in: query
        name: distributionProfile[asperaPrivateKey]
      - in: query
        name: distributionProfile[asperaPublicKey]
      - in: query
        name: distributionProfile[assetFilenameXslt]
      - in: query
        name: distributionProfile[assumeSuccess]
      - in: query
        name: distributionProfile[autoCreateFlavors]
        description: Comma separated flavor params ids that should be auto converted
      - in: query
        name: distributionProfile[autoCreateThumb]
        description: Comma separated thumbnail params ids that should be auto generated
      - in: query
        name: distributionProfile[backgroundImageStandard]
      - in: query
        name: distributionProfile[backgroundImageWide]
      - in: query
        name: distributionProfile[basePath]
      - in: query
        name: distributionProfile[blockOutsideOwnership]
      - in: query
        name: distributionProfile[bodyXslt]
      - in: query
        name: distributionProfile[captionAutosync]
      - in: query
        name: distributionProfile[categoryId]
      - in: query
        name: distributionProfile[certificateKey]
      - in: query
        name: distributionProfile[channelCopyright]
      - in: query
        name: distributionProfile[channelDescription]
      - in: query
        name: distributionProfile[channelGenerator]
      - in: query
        name: distributionProfile[channelGuid]
        description: The Channel GUID assigned to this Publication Rule
      - in: query
        name: distributionProfile[channelImageHeight]
      - in: query
        name: distributionProfile[channelImageLink]
      - in: query
        name: distributionProfile[channelImageTitle]
      - in: query
        name: distributionProfile[channelImageUrl]
      - in: query
        name: distributionProfile[channelImageWidth]
      - in: query
        name: distributionProfile[channelLanguage]
      - in: query
        name: distributionProfile[channelLink]
      - in: query
        name: distributionProfile[channelManagingEditor]
      - in: query
        name: distributionProfile[channelRating]
      - in: query
        name: distributionProfile[channelTitle]
      - in: query
        name: distributionProfile[claimType]
      - in: query
        name: distributionProfile[commercialPolicy]
      - in: query
        name: distributionProfile[contactEmail]
      - in: query
        name: distributionProfile[contactTelephone]
      - in: query
        name: distributionProfile[contentOwner]
      - in: query
        name: distributionProfile[copyright]
      - in: query
        name: distributionProfile[cPlatformTvSeriesField]
      - in: query
        name: distributionProfile[cPlatformTvSeries]
      - in: query
        name: distributionProfile[csId]
      - in: query
        name: distributionProfile[cuePointsProvider]
      - in: query
        name: distributionProfile[defaultCategory]
      - in: query
        name: distributionProfile[deleteEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: distributionProfile[deleteReference]
      - in: query
        name: distributionProfile[disableEpisodeNumberCustomValidation]
      - in: query
        name: distributionProfile[disableMetadata]
      - in: query
        name: distributionProfile[distributeCaptions]
      - in: query
        name: distributionProfile[distributeCuePoints]
      - in: query
        name: distributionProfile[distributeRemoteCaptionAssetContent]
      - in: query
        name: distributionProfile[distributeRemoteFlavorAssetContent]
      - in: query
        name: distributionProfile[distributeRemoteThumbAssetContent]
      - in: query
        name: distributionProfile[domainGuid]
        description: The GUID of the Customer Domain in the Unicorn system obtained
          by contacting your Unicorn representative
      - in: query
        name: distributionProfile[domainName]
        description: The name of the Domain that the Upload User should have access
          to, Used for authentication
      - in: query
        name: distributionProfile[domain]
      - in: query
        name: distributionProfile[downloadPriceCode]
      - in: query
        name: distributionProfile[email]
      - in: query
        name: distributionProfile[enableAdServer]
      - in: query
        name: distributionProfile[entitlements]
      - in: query
        name: distributionProfile[entitlement]
      - in: query
        name: distributionProfile[feedAuthorName]
      - in: query
        name: distributionProfile[feedCopyright]
      - in: query
        name: distributionProfile[feedDescription]
      - in: query
        name: distributionProfile[feedImageHeight]
      - in: query
        name: distributionProfile[feedImageLink]
      - in: query
        name: distributionProfile[feedImageTitle]
      - in: query
        name: distributionProfile[feedImageUrl]
      - in: query
        name: distributionProfile[feedImageWidth]
      - in: query
        name: distributionProfile[feedLanguage]
      - in: query
        name: distributionProfile[feedLastBuildDate]
      - in: query
        name: distributionProfile[feedLink]
      - in: query
        name: distributionProfile[feedSpecVersion]
        description: 'Enum Type: `KalturaYouTubeDistributionFeedSpecVersion`'
      - in: query
        name: distributionProfile[feedSubtitle]
      - in: query
        name: distributionProfile[feedTitle]
      - in: query
        name: distributionProfile[fieldConfigArray]
      - in: query
        name: distributionProfile[flavorAssetFilenameXslt]
      - in: query
        name: distributionProfile[flvFlavorParamsId]
      - in: query
        name: distributionProfile[ftpHost]
      - in: query
        name: distributionProfile[ftpLogin]
      - in: query
        name: distributionProfile[ftpPassword]
      - in: query
        name: distributionProfile[ftpPass]
      - in: query
        name: distributionProfile[ftpPath]
      - in: query
        name: distributionProfile[ftpUsername]
      - in: query
        name: distributionProfile[genericProviderId]
        description: '`insertOnly`'
      - in: query
        name: distributionProfile[geoBlockingMapping]
        description: 'Enum Type: `KalturaDailymotionGeoBlockingMapping`'
      - in: query
        name: distributionProfile[googleClientId]
      - in: query
        name: distributionProfile[googleClientSecret]
      - in: query
        name: distributionProfile[googleTokenData]
      - in: query
        name: distributionProfile[hideViewCount]
      - in: query
        name: distributionProfile[host]
      - in: query
        name: distributionProfile[ignoreSchedulingInFeed]
      - in: query
        name: distributionProfile[ingestUrl]
      - in: query
        name: distributionProfile[instreamStandard]
      - in: query
        name: distributionProfile[instreamTrueview]
      - in: query
        name: distributionProfile[ips]
      - in: query
        name: distributionProfile[itemLink]
      - in: query
        name: distributionProfile[itemMediaRating]
      - in: query
        name: distributionProfile[itemsPerPage]
      - in: query
        name: distributionProfile[itemType]
      - in: query
        name: distributionProfile[itemXpathsToExtend]
      - in: query
        name: distributionProfile[mapAccessControlProfileIds]
      - in: query
        name: distributionProfile[mapCaptionParamsIds]
      - in: query
        name: distributionProfile[mapConversionProfileIds]
      - in: query
        name: distributionProfile[mapFlavorParamsIds]
      - in: query
        name: distributionProfile[mapMetadataProfileIds]
      - in: query
        name: distributionProfile[mapStorageProfileIds]
      - in: query
        name: distributionProfile[mapThumbParamsIds]
      - in: query
        name: distributionProfile[metadataFilenameXslt]
      - in: query
        name: distributionProfile[metadataProfileId]
      - in: query
        name: distributionProfile[metadataXpathsTriggerUpdate]
      - in: query
        name: distributionProfile[metadataXslt]
      - in: query
        name: distributionProfile[msnvideoCat]
      - in: query
        name: distributionProfile[msnvideoTopCat]
      - in: query
        name: distributionProfile[msnvideoTop]
      - in: query
        name: distributionProfile[name]
      - in: query
        name: distributionProfile[notificationEmail]
      - in: query
        name: distributionProfile[objectType]
      - in: query
        name: distributionProfile[optionalAssetDistributionRules]
      - in: query
        name: distributionProfile[optionalFlavorParamsIds]
        description: Comma separated flavor params ids that should be submitted if
          ready
      - in: query
        name: distributionProfile[optionalThumbDimensions]
      - in: query
        name: distributionProfile[overrideManualEdits]
      - in: query
        name: distributionProfile[ownerName]
      - in: query
        name: distributionProfile[pageAccessToken]
      - in: query
        name: distributionProfile[pageGroup]
      - in: query
        name: distributionProfile[pageId]
      - in: query
        name: distributionProfile[passphrase]
      - in: query
        name: distributionProfile[password]
      - in: query
        name: distributionProfile[permissions]
      - in: query
        name: distributionProfile[port]
      - in: query
        name: distributionProfile[priority]
      - in: query
        name: distributionProfile[privacyStatus]
      - in: query
        name: distributionProfile[processFeed]
        description: 'Enum Type: `KalturaYahooDistributionProcessFeedActionStatus`'
      - in: query
        name: distributionProfile[protocol]
        description: '`insertOnly`Enum Type: `KalturaDistributionProtocol`'
      - in: query
        name: distributionProfile[providerId]
      - in: query
        name: distributionProfile[providerName]
      - in: query
        name: distributionProfile[providerType]
        description: '`insertOnly`Enum Type: `KalturaDistributionProviderType`'
      - in: query
        name: distributionProfile[rating]
      - in: query
        name: distributionProfile[recommendedDcForDownload]
        description: The best Kaltura data center to be used to download the asset
          files to
      - in: query
        name: distributionProfile[recommendedDcForExecute]
        description: The best Kaltura data center to be used to execute the distribution
          job
      - in: query
        name: distributionProfile[recommendedStorageProfileForDownload]
        description: The best external storage to be used to download the asset files
          from
      - in: query
        name: distributionProfile[releaseClaims]
      - in: query
        name: distributionProfile[remoteAssetParamsId]
        description: The flavor-params that will be used for the remote asset
      - in: query
        name: distributionProfile[replaceAirDates]
      - in: query
        name: distributionProfile[replaceGroup]
      - in: query
        name: distributionProfile[reportEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: distributionProfile[requiredAssetDistributionRules]
      - in: query
        name: distributionProfile[requiredFlavorParamsIds]
        description: Comma separated flavor params ids that required to be ready before
          submission
      - in: query
        name: distributionProfile[requiredThumbDimensions]
      - in: query
        name: distributionProfile[reRequestPermissions]
      - in: query
        name: distributionProfile[seasonNumber]
      - in: query
        name: distributionProfile[seasonSynopsis]
      - in: query
        name: distributionProfile[seasonTuneInInformation]
      - in: query
        name: distributionProfile[sendMetadataAfterAssets]
      - in: query
        name: distributionProfile[seriesAdditionalCategories]
      - in: query
        name: distributionProfile[seriesChannel]
      - in: query
        name: distributionProfile[seriesPrimaryCategory]
      - in: query
        name: distributionProfile[sftpBaseDir]
      - in: query
        name: distributionProfile[sftpBasePath]
      - in: query
        name: distributionProfile[sftpHost]
      - in: query
        name: distributionProfile[sftpLogin]
      - in: query
        name: distributionProfile[sftpPass]
      - in: query
        name: distributionProfile[sftpPort]
      - in: query
        name: distributionProfile[sftpPrivateKey]
      - in: query
        name: distributionProfile[sftpPublicKey]
      - in: query
        name: distributionProfile[shouldAddThumbExtension]
      - in: query
        name: distributionProfile[shouldIncludeCaptions]
      - in: query
        name: distributionProfile[shouldIncludeCuePoints]
      - in: query
        name: distributionProfile[slFlavorParamsId]
      - in: query
        name: distributionProfile[slHdFlavorParamsId]
      - in: query
        name: distributionProfile[sourceFlavorParamsId]
      - in: query
        name: distributionProfile[sourceFriendlyName]
      - in: query
        name: distributionProfile[source]
      - in: query
        name: distributionProfile[state]
      - in: query
        name: distributionProfile[status]
        description: 'Enum Type: `KalturaDistributionProfileStatus`'
      - in: query
        name: distributionProfile[storageProfileId]
        description: The remote storage that should be used for the remote asset
      - in: query
        name: distributionProfile[streamingPriceCode]
      - in: query
        name: distributionProfile[strict]
      - in: query
        name: distributionProfile[submitAction][ftpPassiveMode]
      - in: query
        name: distributionProfile[submitAction][httpFieldName]
      - in: query
        name: distributionProfile[submitAction][httpFileName]
      - in: query
        name: distributionProfile[submitAction][password]
      - in: query
        name: distributionProfile[submitAction][protocol]
        description: 'Enum Type: `KalturaDistributionProtocol`'
      - in: query
        name: distributionProfile[submitAction][serverPath]
      - in: query
        name: distributionProfile[submitAction][serverUrl]
      - in: query
        name: distributionProfile[submitAction][username]
      - in: query
        name: distributionProfile[submitEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: distributionProfile[sunriseDefaultOffset]
        description: If entry distribution sunrise not specified that will be the
          default since entry creation time, in seconds
      - in: query
        name: distributionProfile[sunsetDefaultOffset]
        description: If entry distribution sunset not specified that will be the default
          since entry creation time, in seconds
      - in: query
        name: distributionProfile[tags]
      - in: query
        name: distributionProfile[targetAccountId]
      - in: query
        name: distributionProfile[targetLoginId]
      - in: query
        name: distributionProfile[targetLoginPassword]
      - in: query
        name: distributionProfile[targetServiceUrl]
      - in: query
        name: distributionProfile[target]
      - in: query
        name: distributionProfile[thumbnailAssetFilenameXslt]
      - in: query
        name: distributionProfile[ugcPolicy]
      - in: query
        name: distributionProfile[updateEnabled]
        description: 'Enum Type: `KalturaDistributionProfileActionStatus`'
      - in: query
        name: distributionProfile[upstreamNetworkId]
      - in: query
        name: distributionProfile[upstreamNetworkName]
      - in: query
        name: distributionProfile[upstreamVideoId]
      - in: query
        name: distributionProfile[urgentReference]
      - in: query
        name: distributionProfile[useCategoryEntries]
        description: When checking custom XSLT conditions using the fieldConfigArray
          - address only categories associated with the entry via the categoryEntry
          object
      - in: query
        name: distributionProfile[userAccessToken]
      - in: query
        name: distributionProfile[username]
      - in: query
        name: distributionProfile[user]
      - in: query
        name: distributionProfile[videoMediaType]
      - in: query
        name: distributionProfile[wmvFlavorParamsId]
      - in: query
        name: distributionProfile[xsltFile]
      - in: query
        name: distributionProfile[xsl]
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Distributionprofile
      - Action
      - Update
  /service/contentdistribution_distributionprofile/action/updateStatus:
    get:
      summary: Get Service Contentdistribution Distributionprofile Action Updatestatus
      description: Update Distribution Profile status by id
      operationId: distributionProfile.updateStatus
      x-api-path-slug: servicecontentdistribution-distributionprofileactionupdatestatus-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      - in: query
        name: status
        description: 'Enum Type: `KalturaDistributionProfileStatus`'
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Distributionprofile
      - Action
      - UpdateStatus
  /service/contentdistribution_distributionprovider/action/list:
    get:
      summary: Get Service Contentdistribution Distributionprover Action List
      description: List all distribution providers
      operationId: distributionProvider.list
      x-api-path-slug: servicecontentdistribution-distributionprovideractionlist-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[isDefaultEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[isDefaultIn]
      - in: query
        name: filter[objectType]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[partnerIdEqual]
      - in: query
        name: filter[partnerIdIn]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaGenericDistributionProviderStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[typeEqual]
        description: 'Enum Type: `KalturaDistributionProviderType`'
      - in: query
        name: filter[typeIn]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Distributionprovider
      - Action
      - List
  /service/contentdistribution_entrydistribution/action/add:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Add
      description: Add new Entry Distribution
      operationId: entryDistribution.add
      x-api-path-slug: servicecontentdistribution-entrydistributionactionadd-get
      parameters:
      - in: query
        name: entryDistribution[assetIds]
        description: Comma separated asset ids
      - in: query
        name: entryDistribution[distributionProfileId]
        description: '`insertOnly`'
      - in: query
        name: entryDistribution[entryId]
        description: '`insertOnly`'
      - in: query
        name: entryDistribution[flavorAssetIds]
        description: Comma separated flavor asset ids
      - in: query
        name: entryDistribution[sunrise]
        description: Entry distribution publish time as Unix timestamp (In seconds)
      - in: query
        name: entryDistribution[sunset]
        description: Entry distribution un-publish time as Unix timestamp (In seconds)
      - in: query
        name: entryDistribution[thumbAssetIds]
        description: Comma separated thumbnail asset ids
      - in: query
        name: entryDistribution[validationErrors]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - Add
  /service/contentdistribution_entrydistribution/action/delete:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Delete
      description: Delete Entry Distribution by id
      operationId: entryDistribution.delete
      x-api-path-slug: servicecontentdistribution-entrydistributionactiondelete-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - Delete
  /service/contentdistribution_entrydistribution/action/get:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Get
      description: Get Entry Distribution by id
      operationId: entryDistribution.get
      x-api-path-slug: servicecontentdistribution-entrydistributionactionget-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - Get
  /service/contentdistribution_entrydistribution/action/list:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action List
      description: List all distribution providers
      operationId: entryDistribution.list
      x-api-path-slug: servicecontentdistribution-entrydistributionactionlist-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[dirtyStatusEqual]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[dirtyStatusIn]
      - in: query
        name: filter[distributionProfileIdEqual]
      - in: query
        name: filter[distributionProfileIdIn]
      - in: query
        name: filter[entryIdEqual]
      - in: query
        name: filter[entryIdIn]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[submittedAtGreaterThanOrEqual]
      - in: query
        name: filter[submittedAtLessThanOrEqual]
      - in: query
        name: filter[sunriseGreaterThanOrEqual]
      - in: query
        name: filter[sunriseLessThanOrEqual]
      - in: query
        name: filter[sunsetGreaterThanOrEqual]
      - in: query
        name: filter[sunsetLessThanOrEqual]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - List
  /service/contentdistribution_entrydistribution/action/retrySubmit:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Retrysubmit
      description: Retries last submit action
      operationId: entryDistribution.retrySubmit
      x-api-path-slug: servicecontentdistribution-entrydistributionactionretrysubmit-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - RetrySubmit
  /service/contentdistribution_entrydistribution/action/serveReturnedData:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Servereturneddata
      description: Serves entry distribution returned data
      operationId: entryDistribution.serveReturnedData
      x-api-path-slug: servicecontentdistribution-entrydistributionactionservereturneddata-get
      parameters:
      - in: query
        name: actionType
        description: 'Enum Type: `KalturaDistributionAction`'
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - ServeReturnedData
  /service/contentdistribution_entrydistribution/action/serveSentData:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Servesentdata
      description: Serves entry distribution sent data
      operationId: entryDistribution.serveSentData
      x-api-path-slug: servicecontentdistribution-entrydistributionactionservesentdata-get
      parameters:
      - in: query
        name: actionType
        description: 'Enum Type: `KalturaDistributionAction`'
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - ServeSentData
  /service/contentdistribution_entrydistribution/action/submitAdd:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Submitadd
      description: Submits Entry Distribution to the remote destination
      operationId: entryDistribution.submitAdd
      x-api-path-slug: servicecontentdistribution-entrydistributionactionsubmitadd-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      - in: query
        name: submitWhenReady
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - Submit
  /service/contentdistribution_entrydistribution/action/submitDelete:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Submitdelete
      description: Deletes Entry Distribution from the remote destination
      operationId: entryDistribution.submitDelete
      x-api-path-slug: servicecontentdistribution-entrydistributionactionsubmitdelete-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - Submit
  /service/contentdistribution_entrydistribution/action/submitFetchReport:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Submitfetchreport
      description: Submits Entry Distribution report request
      operationId: entryDistribution.submitFetchReport
      x-api-path-slug: servicecontentdistribution-entrydistributionactionsubmitfetchreport-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - SubmitFetchReport
  /service/contentdistribution_entrydistribution/action/submitUpdate:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Submitupdate
      description: Submits Entry Distribution changes to the remote destination
      operationId: entryDistribution.submitUpdate
      x-api-path-slug: servicecontentdistribution-entrydistributionactionsubmitupdate-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - Submit
  /service/contentdistribution_entrydistribution/action/update:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Update
      description: Update Entry Distribution by id
      operationId: entryDistribution.update
      x-api-path-slug: servicecontentdistribution-entrydistributionactionupdate-get
      parameters:
      - in: query
        name: entryDistribution[assetIds]
        description: Comma separated asset ids
      - in: query
        name: entryDistribution[distributionProfileId]
        description: '`insertOnly`'
      - in: query
        name: entryDistribution[entryId]
        description: '`insertOnly`'
      - in: query
        name: entryDistribution[flavorAssetIds]
        description: Comma separated flavor asset ids
      - in: query
        name: entryDistribution[sunrise]
        description: Entry distribution publish time as Unix timestamp (In seconds)
      - in: query
        name: entryDistribution[sunset]
        description: Entry distribution un-publish time as Unix timestamp (In seconds)
      - in: query
        name: entryDistribution[thumbAssetIds]
        description: Comma separated thumbnail asset ids
      - in: query
        name: entryDistribution[validationErrors]
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - Update
  /service/contentdistribution_entrydistribution/action/validate:
    get:
      summary: Get Service Contentdistribution Entrydistribution Action Valate
      description: Validates Entry Distribution by id for submission
      operationId: entryDistribution.validate
      x-api-path-slug: servicecontentdistribution-entrydistributionactionvalidate-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Entrydistribution
      - Action
      - Validate
  /service/contentdistribution_genericdistributionprovider/action/add:
    get:
      summary: Get Service Contentdistribution Genericdistributionprover Action Add
      description: Add new Generic Distribution Provider
      operationId: genericDistributionProvider.add
      x-api-path-slug: servicecontentdistribution-genericdistributionprovideractionadd-get
      parameters:
      - in: query
        name: genericDistributionProvider[availabilityUpdateEnabled]
      - in: query
        name: genericDistributionProvider[deleteInsteadUpdate]
      - in: query
        name: genericDistributionProvider[editableFields]
      - in: query
        name: genericDistributionProvider[intervalBeforeSunrise]
      - in: query
        name: genericDistributionProvider[intervalBeforeSunset]
      - in: query
        name: genericDistributionProvider[isDefault]
      - in: query
        name: genericDistributionProvider[mandatoryFields]
      - in: query
        name: genericDistributionProvider[name]
      - in: query
        name: genericDistributionProvider[optionalFlavorParamsIds]
      - in: query
        name: genericDistributionProvider[optionalThumbDimensions]
      - in: query
        name: genericDistributionProvider[requiredFlavorParamsIds]
      - in: query
        name: genericDistributionProvider[requiredThumbDimensions]
      - in: query
        name: genericDistributionProvider[scheduleUpdateEnabled]
      - in: query
        name: genericDistributionProvider[updateRequiredEntryFields]
      - in: query
        name: genericDistributionProvider[updateRequiredMetadataXPaths]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Contentdistribution
      - Genericdistributionprovider
      - Action
      - Add
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---