# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '104bd85d990155f04f050972374a3502b4631830',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'c98e976b567735776a4dc692bc744231dae4b13a',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '54a521dd130ae1b2f38fef79b09515702d135bdd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f2dac2f3dea4464dd50cd7793c8c3d7e51dc7e24',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '952f776f6573aafbb62ea717d871cd1d6816c387',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '809941a4ca137df69dc9c6e8eb456bd70309197c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'dbe142e8f3a7f11478c2e4741c0d4c4b748fce4b',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'c4ede3c60031486d611d5f9073abac7901f1c69a',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '352e3efb64e3075d0d6813c8ead663539b4e14a5',
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
