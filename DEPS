# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '5b226551be1f4f4595eb3aa9a7e300df870baa82',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'dcbd02e0e7a6ed2892af97bfeb3c9871c53fd7de',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f88a2d766840fc825af1fc065977953ba1fa4a91',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '3173273e78edeeacaae9d752afa2151e44af5f65',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'ad9ce1235e88dc09287e19171dfac384db8ec32c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '1338b8ee2ad29446297e7368370eecabd4890bec',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '39a19dccf79d28951516c3c7c9f1ee4a606fb733',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '738ec97a3f659dd6469bff3c4078ef981b0a343f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'aea1bd8238153bc47b7c657d1b2d92fa91d45c31',
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
