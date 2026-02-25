# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'e966816ab28ab7cb448d5b33270b43c941b343d4',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'dcbd02e0e7a6ed2892af97bfeb3c9871c53fd7de',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f88a2d766840fc825af1fc065977953ba1fa4a91',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'e63ee307a0cbcd42fd8d80aa3c716e8159ac13aa',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'ad9ce1235e88dc09287e19171dfac384db8ec32c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '2fbfccc8979a9382d60c4b3781c27702f2ca3c0b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6a9d187173f2ec4773da1e7e9cae587f6390d817',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '738ec97a3f659dd6469bff3c4078ef981b0a343f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '636e3c157253193c6aa1515047dc33ac0b6f620d',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
