# AInSights-IDP
List of image derived phenotypes for AInSights

* pyradiomics - full details may be found [here](https://pyradiomics.readthedocs.io/en/latest/features.html)

    * First Order Statistics (first order)
        * 10Percentile
        * 90Percentile
        * Energy
        * Entropy
        * InterquartileRange
        * Kurtosis
        * Maximum
        * MeanAbsoluteDeviation
        * Mean
        * Median
        * Minimum
        * Range
        * RobustMeanAbsoluteDeviation
        * RootMeanSquared
        * Skewness
        * TotalEnergy
        * Uniformity
        * Variance
    * Shape-based 3D (shape)
        * Elongation
        * Flatness
        * Least Axis Length
        * Major Axis Length
        * Maximum2DDiameterColumn
        * Maximum2DDiameterRow
        * Maximum2DDiameterSlice
        * Maximum3DDiameter
        * MeshVolume
        * MinorAxisLength
        * Sphericity
        * SurfaceArea
        * SurfaceVolumeRatio
        * VoxelVolume
        * OnBorder
    * Gray Level Co-occurance matrix (glcm)
        * Autocorrelation
        * ClusterProminence
        * ClusterShade
        * ClusterTendency
        * Contrast
        * Correlation
        * DifferenceAverage
        * DifferenceEntropy
        * DifferenceVariance
        * Id
        * Idm
        * Idmn
        * Idn
        * Imc1
        * Imc2
        * InverseVariance
        * JointAverage
        * JointEnergy
        * JointEntropy
        * MCC
        * MaximumProbability
        * SumAverage
        * SumEntropy
        * SumSquares
    * Gray Level Dependence Matrix (gldm)
        * DependenceEntropy
        * DependenceNonUniformity
        * DependenceNonUniformityNormalized
        * DependenceVariance
        * GrayLevelNonUniformity
        * GrayLevelVariance
        * HighGrayLevelEmphasis
        * LargeDependenceEmphasis
        * LargeDependenceHighGrayLevelEmphasis
        * LargeDependenceLowGrayLevelEmphasis
        * LowGrayLevelEmphasis
        * SmallDependenceEmphasis
        * SmallDependenceHighGrayLevelEmphasis
        * SmallDependenceLowGrayLevelEmphasis
    * Gray Level Run Length Matrix (glrlm)
        * GrayLevelNonUniformity
        * GrayLevelNonUniformityNormalized
        * GrayLevelVariance
        * HighGrayLevelRunEmphasis
        * LongRunEmphasis
        * LongRunHighGrayLevelEmphasis
        * LongRunLowGrayLevelEmphasis
        * LowGrayLevelRunEmphasis
        * RunEntropy
        * RunLengthNonUniformity
        * RunLengthNonUniformityNormalized
        * RunPercentage
        * RunVariance
        * ShortRunEmphasis
        * ShortRunHighGrayLevelEmphasis
        * ShortRunLowGrayLevelEmphasis
    * Gray Level Size Zone Matrix (glszm)
        * GrayLevelNonUniformity
        * GrayLevelNonUniformityNormalized
        * GrayLevelVariance
        * HighGrayLevelZoneEmphasis
        * LargeAreaEmphasis
        * LargeAreaHighGrayLevelEmphasis
        * LargeAreaLowGrayLevelEmphasis
        * LowGrayLevelZoneEmphasis
        * SizeZoneNonUniformity
        * SizeZoneNonUniformityNormalized
        * SmallAreaEmphasis
        * SmallAreaHighGrayLevelEmphasis
        * SmallAreaLowGrayLevelEmphasis
        * ZoneEntropy
        * ZonePercentage
        * ZoneVariance
    * Neighboring Gray Tone Difference Matrix (ngtdm)
        * Busyness
        * Coarseness
        * Complexity
        * Contrast
        * Strength
* SimpleITK
    * intensity
        * Mean
        * Minimum
        * Maximum
        * Median
        * StandardDeviation
    * shape
        * Volume
        * Roundness
        * Skewness
        * Elongation
        * Flatness
        * WeightedElongation
        * WeightedFlatness
        * Kurtosis
        * EllipsoidDiameter0
        * EllipsoidDiameter1
        * EllipsoidDiameter2
        * EquivalentSphericalRadius
        * EquivalentSphericalPerimeter
        * FeretDiameter
        * NumberOfPixels
        * GetNumberOfPixelsOnBorder
        * PerimeterOnBorder
        * PerimeterOnBorderRatio
        * Perimeter

Image Parameters

* Properties as read in by ITK
    * Filename
    * ImageDimension
    * NumberOfComponentsPerPixel
    * Spacing_0
    * Spacing_1
    * Spacing_2
    * Origin_0
    * Origin_1
    * Origin_2
    * Direction_0
    * Direction_1
    * Direction_2
    * Direction_3
    * Direction_4
    * Direction_5
    * Direction_6
    * Direction_7
    * Direction_8
    * Size_0
    * Size_1
    * Size_2
* Properties from dicom files
    * AccessionNumber_0
    * StudyTime_0
    * SeriesTime_0
    * Modality_0
    * Manufacturer_0
    * InstitutionName_0
    * StationName_0
    * StudyDescription_0
    * ProcedureCodeSequence_00080100_0
    * ProcedureCodeSequence_00080102_0
    * ProcedureCodeSequence_00080104_0
    * SeriesDescription_0
    * ManufacturerModelName_0
    * PatientSex_0
    * PatientAge_0
    * ContrastBolusAgent_0
    * BodyPartExamined_0
    * KVP_0
    * DataCollectionDiameter_0
    * DeviceSerialNumber_0
    * SoftwareVersions_0
    * ProtocolName_0
    * ContrastBolusVolume_0
    * ContrastBolusStartTime_0
    * ContrastBolusStopTime_0
    * ContrastBolusTotalDose_0
    * ContrastFlowRate_0
    * ContrastFlowDuration_0
    * ContrastBolusIngredientConcentration_0
    * ReconstructionDiameter_0
    * DistanceSourceToDetector_0
    * DistanceSourceToPatient_0
    * GantryDetectorTilt_0
    * RotationDirection_0
    * ExposureTime_0
    * Exposure_0
    * XRayTubeCurrent_0
    * FilterType_0
    * GeneratorPower_0
    * FocalSpots_0
    * ConvolutionKernel_0
    * ConvolutionKernel_1
    * PatientPosition_0
    * SingleCollimationWidth_0
    * TotalCollimationWidth_0
    * TableSpeed_0
    * TableFeedPerRotation_0
    * SpiralPitchFactor_0
    * ExposureModulationType_0
    * StudyID_0
    * SeriesNumber_0
    * RequestedProcedureDescription_0
    * RevolutionTime_0
    * ContrastBolusRoute_0
    * FocalSpots_1
    * PatientOrientation_0
    * PatientOrientation_1
    * PatientPosition_1
    * PatientPosition_2
    * SoftwareVersions_1
    * SoftwareVersions_2