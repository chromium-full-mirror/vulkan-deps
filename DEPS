# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '48eaea60b849e3eb9ff970b7d4e873646b658863',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '9c5393aa32a1bede1d00c322f4fd007bcafa2f79',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '3c355ec439dcf821c50fb4660ef0e50d19ae2b63',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '7c778973e5eb56ef735bf1a3ad96865eb261997d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'b379292b2ab6df5771ba9870d53cf8b2c9295daf',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'e77a24e467d6cd3dbd949dedd057bc7c8b940a69',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '53a6ba7c235cbe0b0f3e85e3de6d9070bcfec710',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '5f26cf65a18bc89a8e3d6569c14314b6fdac8d4d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'ac2e01fc1a67329da0c879ecd2296b76643c49c0',
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
