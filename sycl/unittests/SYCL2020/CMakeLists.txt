set(CMAKE_CXX_EXTENSIONS OFF)

add_sycl_unittest(SYCL2020Tests OBJECT
  GetNativeOpenCL.cpp
  SpecializationConstant.cpp
  KernelBundle.cpp
  KernelBundleStateFiltering.cpp
  KernelID.cpp
  HasExtension.cpp
  IsCompatible.cpp
  DeviceGetInfoAspects.cpp
  DeviceAspectTraits.cpp
  AtomicMemoryOrderCapabilities.cpp
  AtomicMemoryScopeCapabilities.cpp
  AtomicFenceCapabilities.cpp
)

